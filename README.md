PikadayTime
========

Pickaday with timepicker.

Lightweight date and time picker based on  http://dbushell.github.io/Pikaday

<p><a href="http://dio-el-claire.github.io/PikadayTime/">PikadayTime demo and docs</a></p>

Timepicker options
* `showTime` default is false
* `showSeconds` default is false,
* `hours24format` default is true,
* `minutesStep` default is 1,
* `secondsStep` default is 1,

Timepicker methods

`setTime(new Date())` set time from Date object
`setTime(hours, minutes, seconds)` set hours/minutes/seconds

Other improvement
* redraw datepicker after minDate/maxDate did change.
* i18n moved into Pikaday.prototype
