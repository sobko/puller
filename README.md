## Puller ##

This script is for teachers of CS50AP.  It will let you pull all the student folders for a single assignment, into a folder that you name.  There are a few requirements that your workspace must meet.

- Put a folder at the root of your workspace called "studentwork".  
- Put a file in the same folder as puller.py called names.txt.  This file should have the github names of your students, along with the names you want their folders to have.  It should look like this:

Githubname1,foldername1

Githubname2,foldername2

etc.

At the moment, if a student has not turned in an assignment, puller does not notify the user.  There will simply not be a folder created for that user.

Run the script with "python puller.py".  The script will prompt you for the slug of the assignment, which you can find at cs50.me.  


