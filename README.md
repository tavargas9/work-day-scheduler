# Work Day Scheduler
![badge](https://img.shields.io/badge/MIT-License-blue.svg) ![Awesome](https://awesome.re/badge.svg)

A simple daily planner application that allows the user to save items to their work day schedule on a per hour basis (9am-5pm).

## Table of Contents

- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Usage](#usage)
- [Technologies used](#technologies-used)
- [License](#license)

## User Story

```md
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively
```

## Acceptance Criteria

```md
GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours of 9am-5pm
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist
```

## Usage

To use this application, go to the deployed website [here](https://tavargas9.github.io/work-day-scheduler/).

![Screenshot 2023-09-25 at 8 50 52 PM](https://github.com/tavargas9/work-day-scheduler/assets/142061829/79914004-b8c8-44a6-8a83-87a6427a55af)

- Each hour is color coded by whether it is in past (grey), present (red), or future (green).
- To add an event to your schedule, type it into the text box and click the corresponding "save" icon to the right of the box. The event will be saved to local storage.
- To edit or change an event, click on the corresponding text box and change/add text. Hit the "save" icon and the changes will be saved to local storage.
- To clear your schedule, hit the "Clear items" button at the top of the page.


## Technologies Used

HTML, CSS, JavaScript, jQuery, Bootstrap, Day.js

## License

This is available under the MIT License. See LICENSE in the repo for more information.
