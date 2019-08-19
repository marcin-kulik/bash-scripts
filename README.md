# This script allows to find files that contain non ascii characters.

This script is a mac-version as it is using ***ggrep***

Usage: ascii [OPTION]... PATTERNS

        Search for non-ascii characters in files within the current or chosen directory and all subdirectories.
        Example: ascii -e txt,html,js
            -e, --extension         chose extensions for searched files, seperate multiple extensions by comma, do not use whitespace
            -d, --directory         chose the path of the folder in which you want to search for non-ascii files
            -i, --ignore            chose files to be excluded from the result of your search, seperate multiple files by comma
       
