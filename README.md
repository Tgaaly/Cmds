# Useful Commands

### string search
grep "scipy" *.py

### recursive string search (recursively through directory tree rooted at current dir)
grep -r "scipy" *.py      

### reduce size of pdf
gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dNOPAUSE -dQUIET -dBATCH -sOutputFile=foo-compressed.pdf foo.pdf

### unzip

unzip file.zip -d destination_folder

### list screens

screen -list

### create new screen

screen -S new_session_name

### reconnect to screen

screen -R session_name

### delete dettached session

screen -X -S session_name quit
