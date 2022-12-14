# Progress Bars

## Introduction

`jellog-progress-bar` is the jellog tag for progress bar status.

Basic usage:

````xml
<jellog-progress-bar value="70" />

<jellog-progress-bar type="Warning" value="25"> %25 </jellog-progress-bar>

<jellog-progress-bar type="Success" value="40" strip="true"/>

<jellog-progress-bar type="Dark" value="10" min-value="5" max-value="15" strip="true"> %50 </jellog-progress-bar>

<jellog-progress-group>
    <jellog-progress-part type="Success" value="25"/>
    <jellog-progress-part type="Danger" value="10" strip="true"> %10 </jellog-progress-part>
    <jellog-progress-part type="Primary" value="50" animation="true" strip="true" />
</jellog-progress-group>
````



## Demo

See the [progress bars demo page](https://bootstrap-taghelpers.jellog.io/Components/Progressbars) to see it in action.

## Attributes

### value

A value indicates the current progress of the bar.

### type

A value indicates the background color of the progress bar. Should be one of the following values:

* `Default` (default value)
* `Secondary`
* `Success`
* `Danger`
* `Warning`
* `Info`
* `Light`
* `Dark`

### min-value

Minimum value of the progress bar. Default is 0.

### max-value

Maximum value of the progress bar. Default is 100.

### strip

A value indicates if the background style of the progress bar is stripped. Should be one of the following values:

* `false` (default value)
* `true`

### animation

A value indicates if the stripped background style of the progress bar is animated. Should be one of the following values:

* `false` (default value)
* `true`
