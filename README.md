# todoistAddon
A little library of Python scripts that utilize the Todoist API to accomplish helpful tasks. Though currently consisting of only one script, I'm eager to take your suggestions for new ideas.

This library comes with no license. Feel free to use, adapt, and profit in any way.

See below for descriptions on the script(s) and how to use them.

tdlabel.py
---------------------

tdlabel will add a label of your choosing to all of your tasks in a given project and its subprojects. I use this to ensure all tasks in my "Work" project have a 'work' label, allowing me to apply filters to segregate my work life from my personal life.

To use, download the script and run it using a [python 2.7 interpreter](https://www.python.org/downloads/). You'll need to provide your API key (found in Todoist Settings --> Account), the name of the label you want to add to your tasks, and the name of the parent project whose tasks will get the label, along with the tasks in the children projects. For repeated use, I would recommend hardcoding at least your API key into the script.  
