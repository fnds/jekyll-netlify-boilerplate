---
layout: post
title: cwrap.sh - cron wrapper
author: fnds
date: 2022-03-23 16:55:09
---
The cwrap.sh utility makes it very easy to automate any command or script and execute it using cron. No changes are required on the script to get it to work with cwrap.sh and cron. The utility automatically runs it, saves the output, and sends an email to a designated recipient, if so desired. The log files are tagged with date and time. All the behavior is controlled through configuration files or command line options.

More details on [Github](https://github.com/fnds/cwrap)

[Download cwrap.sh](https://raw.githubusercontent.com/fnds/cwrap/master/cwrap.sh)