# MeetYourNextMSP Data 2021

## To browse events

Go to https://meetyournextmsp.scot/

## To add an event - the easy way

Fill out the form on https://meetyournextmsp.scot/contribute

## To add an event - the technical way

Create a new directory in `events` - the name of this directory should be an id, with letters, numbers and dashes only. 

In that directory, create a file called `events.yaml`. Example contents are:

```
title: Scotland’s cycling and sustainable travel hustings
description: Hosted by Cycling UK in Scotland and Pedal on Parliament
start: 2021-04-20 19:00
end: 2021-04-20 20:30
url: http://www.spokes.org.uk/
tags:
  - national
```

To get the Id's of tags, look at the names of directories in the `tags` directory. You can select `national`, or a constituency or a region. Add as many as apply.

Commit this and create a pull request to https://github.com/meetyournextmsp/data-2021 - thank you!
