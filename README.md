# vanilla-javascript-calendar-demo


## Things to fix

* Place github icon next to smily face. (BONUS)
* Translate to english :D
* All functions should be camelCase: "first letter is not capital"
* Review function names and add description if needed
    * convertToMonthName
* Use `Name: ${name}` instead of "Name: " + name (BONUS)
* Assign variables to avoid long lines of code (example line 231)
* Rename 'dayOfWeek' to something like 'firstWeekdayOfMonth'
* Use more verbose variable/functions names, do not abreviate example (daysInMonth could be numberOfDaysInMonth)
* Refactor "convertToMonthName" using this as example:
```
    const date = new Date(2000, arrayMonth, 1);
    const month = date.toLocaleString('default', { month: 'long' });
```