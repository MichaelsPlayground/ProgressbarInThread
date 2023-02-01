# Progressbar in Thread

Source: https://o7planning.org/12745/android-progressbar

In this example, I'm going to create 2 horizontal ProgressBar(s).
The first ProgressBar is put in Determinate mode. It displays a process which the percentage of complete work is indicated.
The second ProgressBar is put in Indeterminate mode. It will show a progress for which you cannot know the percentage of completed work.

In this example, I'm using Thread to do the work, downloading a file, or updating the records in the database, for example. 
Then I use Handler to update information in the interface.

