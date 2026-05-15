### About:

This project contains IT books on various topics collected throughout the years.

### Usage:

1. Add the books to the corresponding subfolder in Books. (must be PDF format)
2. Go inside Scripts and run update to automatically compress and update the boook list. (Requires to be run in Debian based distros)
   2.1 You can run compress only.
   `-t` flag specifies the treshold under wich files are not checked for compression
   `--clean` flag deletes the list of files that were already checked then compresses all the files again.
   `--cleanonly` flag only deletes the list of files that were already checked.
   2.2 You can run generate_md only to update the list of books.
