## TheConBot (https://t.me/furryconventionbot) Guide

### Available Commands

- /guide - Provides a link to this guide
- /changelog - Provides a changelog of updates to the bot, limited to the last 2 updates
- /faq - Common questions and answers
- /listcon countrycode - Show all conventions in a given country. Example "/listcon UK"
- /map conventionname - Show a floorplan of a convention, if one exists. Example "/map cfz" or "/map confuzzled"
- /sched conventionname - Responds with link to schedule of specified convention
- /timeuntil conventionname - Responds with a countdown to the convention date, command is disabled in group chats

## Change Log

### 26-04-22
- /list command deprecated in favour of /guide
- /map command added
- Privacy mode is respected properly
- Modified the returned message when triggering /timeuntil in groups
- Blacklist functionality to prevent malicious actions impacting services

### 25-04-22 
- Fixed error where commands did not action

### 24-04-22
- Countdowns can no longer be activated in groups 
- Countdown messages cannot be forwarded or saved
- Various bugfixes for stability

## Future Features
- Global blacklist funtionality