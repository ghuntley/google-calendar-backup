Google Calendar Backup
=========

A quick and simple way to backup multiple google calendars

Requirements:

* bash
* wget
* google


Usage
---
Configure the backup destination by tweaking the $BACKUPDIR variable

    BACKUPDIR="~/.gcal-archive"

Configure the private ical URL(s) that you wish to backup, format as "{filename}|{url}" one per line:

    #######################################################################################################################
    # name | google private ical URL
    #######################################################################################################################
    main|http://www.google.com/calendar/ical/ghuntley%40ghuntley.com/private-snip-snip/basic.ics
    finance|http://www.google.com/calendar/ical/ghuntley%40ghuntley.com/private-snip-snip/basic.ics

License
---
Copyright 2011 Geoffrey Huntley. All rights reserved.

Redistribution and use, with or without modification, are permitted - no strings attached.

