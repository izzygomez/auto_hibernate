### About
Simple set of files to automate hibernation at night.
To do this, create separate tasks @ "Control Panel > 
System and Security > Administrative Tools > Task Scheduler"
appropriately, i.e. ten_minute_reminder.vbs ten minutes 
before hibernate_computer.bat, and hibernate_computer.bat at 
the time you wish your computer to automatically hibernate

Update: or you can just make a single task with the new hibernate_in_one_min.bat file

## TODO
create .bat or .exe file with one argument that species the time of day to set the auto-hibernation and sets it in Task Scheduler (hell if I know how to do this right now)