## What if a string is in a file where multiple similar looking strings are there but a minor difference which is unable to find via naked eye. You want to find the exact line which is unique and written only once?

-> sort the file first and then pipe it with uniq command with -u flag for printing only unique files.

```bash
sort data.txt | uniq -u
```
