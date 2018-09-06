# Powershell-System-Info
.NAME
    show-systeminfo.ps1
    .SYNOPSIS
    A tool to assist users in providing information to the helpdesk.
    .DESCRIPTION
    This tool helps users help the helpdesk. It gathers all relevent system information and Teamviewer ID and displays it to the users. 
	There are also a number of added tools for troubleshooting network issues, changing default devices, and creating help desk tickets. 
	When creating a help desk ticket, the user is prompted with an easy to use ui to enter their trouble info.
    .NOTES
	Ticket Creation relies on Solarwinds Web Help Desk API. Guide here: http://www.solarwinds.com/documentation/webhelpdesk/docs/whd_api_12.1.0/web%20help%20desk%20api.html
	When a ticket is created, it is posted to a dedicated Slack Channel. Guide Here: https://api.slack.com/
