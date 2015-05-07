# Useful Commands

### string search
grep "scipy" *.py

### recursive string search (recursively through directory tree rooted at current dir)
grep -r "scipy" *.py      

### reduce size of pdf
gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dNOPAUSE -dQUIET -dBATCH -sOutputFile=foo-compressed.pdf foo.pdf


