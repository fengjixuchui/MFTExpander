# MFTExpander
Expand NTFS MFT Zone by creating directories and files (and removes it at the end)

# Usage
```
Usage: mftexpander.exe [DRIVE] [DIRECTORIES] [FILES]
Usage: mftexpander.exe C:  123 456
Usage: mftexpander.exe C:\ 789 1234
```
Where:
*    [C:]  is drive letter to expand NTFS MFT
*    [C:\] is drive letter to expand NTFS MFT
*    [123] is directory count to make
*    [456] is files count to create to each directory

# NOTE:
After the expansion of the zone of the MTF, you need a software system to defragment the ITF zone.

# Writen with Microsoft Visual Studio 2015 Community. Uses .Net Framework 4.6+
# License - MIT
Copyright (c) 2016 h-zone

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

