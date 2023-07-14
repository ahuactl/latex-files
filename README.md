# latex-files
a collection of latex files i created in the one month vacation

# compile
```sh
$ git clone https://github.com/ahuactl/latex-files.git
$ mkdir build
$ cd build
$ find ../ -name "*.tex" -exec sh -c 'pdflatex "{}"' \;
$ mv $(ls | grep "\.pdf$") ../
```
