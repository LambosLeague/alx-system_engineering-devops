0.current_working_directory The script print absolute path of current path. unlike __pwd_ _it uses "readlink -f filename" to priint the full path. in collaboration with "dirname" __dirname" AND "XARGS" _Same thing can be accomplished readlink -f filename | xargs dirname"

1-listit the script implores "ls" to itemize contain of a particular dir

2-bring-me-home This script uses cd ~ the "~" specifies for home directory on linux
