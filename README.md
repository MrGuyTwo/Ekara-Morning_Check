# Ekara-Morning_Check
![Windows](screenshot/badge.svg)

<a href="https://api.ekara.ip-label.net/"><img src="screenshot/cropped-ekara_by_ip-label_full_2.webp"> 

## Description
This [Powershell](https://learn.microsoft.com/powershell/scripting/overview) Checks the status of the [Ekara](https://ekara.ip-label.net/) scenarios over the defined period and sends an email with a report in PDF format, as an attachment.
You can automate this script into a scheduled task to send a daily report, before service opening.

For this, the script uses the Rest [Ekara](https://api.ekara.ip-label.net/) API.

## Screens

![screen](screenshot/Mail.png)

![screen](screenshot/Repport.png)

## Prerequisites

-|version
--|:--:
Ekara plateform|>=24.12
PowerShell|>=5
.NET|>=4
Microsoft EDGE
folders CSS - images - JS
Ekara credentials
SMTP configuration
Mail credentials
Mail Recipients

(Account and password Ekara)

## Download

[github-download]: https://github.com/MrGuyTwo/Ekara-Morning_Check/releases
 - [`Ekara-Morning_Check`][github-download]

## The main function
Methods called : 

- auth/login
- adm-api/scenarios
- results-api/availability

