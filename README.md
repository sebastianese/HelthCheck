# HelthCheck
Checks the health of a server and sends an email report
There is a top section on the script where you should input your email server info. 

##The report will email you and HTML file containing the following:

*Up time
*Os Info
*Ram and CPU
*Disk with less than 10% free
*Top processes 
*Services set as automatic but not started (* this one is critical after patches)
*Connectivity test with internet (this helps you test your network stack)
*NS lookup (this helps you test domain connectivity and DNS health)
*Last 3 reboots (if you receive the report in the middle of the day you can see what process or user rebooted the system)
*Last 15 system errors and warning
*Last 15 Application errors and warning 
