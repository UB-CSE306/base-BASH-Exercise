BASH Exercise

In this repo you will find twelve .txt files.  Each is a plain text (UTF-8) download of a Project Gutenberg book.  Your task is to define a BASH script that will do each of the following:

- rename the file with the book's title
- place each book in a directory whose name is the year of the book's release date

For example, the file 1952-0.txt contains the text of a book whose title is "The Yellow Wallpaper", whose release date was in November 1999.  The script must ensure that there is a directory named 1999, and that it contains a file named The Yellow Wallpaper.txt (i.e. the file 1952-0.txt renamed to The Yellow Wallpaper.txt.

Note that the script must work correctly no matter what files are in the current directory.  It must only consider .txt files, and only those .txt files which contain both a "Title: " entry and a "Release Date:" entry.

The subdirectories whose names are years must not be overwritten if they already exist, but must be created if they do not.  If a directory exists and it already has a file of the same name as one of the renamed Project Gutenberg books the script must overwrite the file.  Already existing files whose names don't clash must not be impacted by running the script.

Questions may come up as you work through the exercise - just ask!
