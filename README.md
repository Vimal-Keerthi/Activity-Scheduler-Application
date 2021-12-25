# Activity-Scheduler-Application

This Activity Scheduler is a simple application used to keep track of our day to day activities.

It is a command-line application which helps the user to record the activities and keep track of his 
progress.

USAGE :
	add 2 hello world - # Add a new item priority 2 and text "hello world" to the list
    ls - # Show incomplete priority list items sorted by priority in ascending order
	del NUMBER - # Delete the incomplete item with the given priority number
	done NUMBER - # Mark the incomplete item with the given priority number as complete
	help - # Show usage
	report - # Statistics
	exit - # Exit from the application


This program consists of the following routines :
1. showUsage() - This module guides the user on how to use the commands.
2. addItem() - This module helps the user to add his/ her activities along with priorities.
3. markDone() - This module marks the specified activity as done and deletes it from the list of activities.
4. deleteItem() - This module works in the same way as markDone(). However, it is used to delete the activities which are not
                    necessary and are to be deleted from the list.
5. showIncomplete() - This module displays all the activities which are not completed.
6. statistics() - This module displays the statistics to the user about the count of activities which are completed and not
                    completed.

