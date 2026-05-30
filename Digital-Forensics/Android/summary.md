Android problems were interesting because they required common sense. Overview of common steps for the problems:

1. Try to assume which databases or files can be relevant with the desired search. Make simple search using the assumed name in simple file explorer.
2. Most of the informations are found in database, but the binary datas of database cannot be extracted and understood as raw form. So, we need to use database viewer (Online or using SQLite)
3. Using simple 'grep' command can be also useful. Sample Command : grep -ri 'relevant_string' 'directory'   [recursive grep command]
4. It'd be better if you can patiently go through all the directories first before diving into the problem.
5. Used this site (https://sqliteviewer.app/) to open the database files (.db).

I used to manipulate android games like by altering the game files in android 'data' folder, which can be found in explorer. I solved the problems using my previous experience of manipulating game data. So, I am yet to learn how android file system actually works.
