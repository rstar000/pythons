# CalcHash

Calculates SHA256 of a file or list of files.

For easy use in Windows, use a batch script in PATH directory (filename = hash.bat).

```batch
@echo off
python "C:\path\to\file\CalcHash.py" %1 %2 %3 %4 %5 %6
```

Then call it from cmd.

```
hash.bat file1.pdf file2.zip
```