# vanilla-javascript-calendar-demo


## Part 1 ✔️
Input month/year and count of number of days.

## Part 2 Code review
* Add basic read.
* Place github icon next to smily face. (BONUS)
* Translate to english :D ✔️
* All functions should be camelCase: "first letter is not capital" ✔️
* Review function names and add description if needed✔️
    * convertToMonthName
* Use `Name: ${name}` instead of "Name: " + name (BONUS) ✔️
* Assign variables to avoid long lines of code (example line 231)✔️
* Rename 'dayOfWeek' to something like 'firstWeekdayOfMonth'✔️
* Use more verbose variable/functions names, do not abreviate example (daysInMonth could be numberOfDaysInMonth)✔️
* Refactor "convertToMonthName" using this as example:✔️
```
    const date = new Date(arrayYear, arrayMonth, 1);
    const month = date.toLocaleString('default', { month: 'long' });
```

* Instead of adding '.first-row', '.last-line-first-row', '.last-line-last-row' to certain calendar day blocks use :nth-child, here is an example:✔️
```
.calendar-day{
    border-right: solid 1px black;
    border-bottom: solid 1px black;
}

.calendar-day:nth-child(8n) {
    border-left: solid 1px black;
}

```

* Use javascript loops to add html for each date instead of manual html. ✔️

## Part 3

Create a modal visually similar to [bootstrap](https://getbootstrap.com/docs/4.0/components/modal/). It must have:

1. A fixed title of "Details for date"
1. Empty message in the body
1. A close button that closes it
1. It should show up over the calendar.
1. The background should become grayed out (a dark glass effect)
1. Clicking on the dark glass should close the modal
1. Clicking on the close button should close it
1. Hover over calendar block should change cursor to pointer and highlight it
1. Clicking on the a day block should open it
1. Pressing ESC should close the modal
1. the with of modal can be fixed at 600px and the height can be defined by the content.
1. There should be a **global function** called openModal() that shows the modal over the calendar
1. There should be a **global function** called closeModal() that closes that modal.
1. HINT: start by making the modal statically open so it is always open. After it looks right, focus on finding a way to show/hide it (think of the visibily cloack from Harry Potter). Read about "position: fixed."

