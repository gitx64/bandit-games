## IF want to find not executable file type and human readable with specific sizes

-> find . -type f -size 1033c ! -executable -exec file {} + | grep -E "text$|ASCII text"

what this command does is find files with size of 1033 bytes which are not executable and type of something which starts with text or an ASCII text type.
