Creates IFTTT Applet Filter based on hour to 'skip' defined Actions.

You need to sign up for IFTTT Platform https://platform.ifttt.com/ , it's free for 'Personal' (unpublished) Applets.

Couple of issues working through

1: "Action skip message" in "View Activity" of the Applet only provides the first message set "Action skip message: Alarm Supressed"

2: "Meta.currentUserTime.hour()" doesn't seem to recognise 0 (as midnight) as Actions are triggered anytime and not skipped when set "if (currentHour >= 0 || currentHour < 5 ) {"


