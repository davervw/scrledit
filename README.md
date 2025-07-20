# Scrolling BASIC Editor for Commodore 64 (Source Code) #

Article and binary program were [originally published](https://archive.org/details/1988-01-computegazette/page/n81/mode/2up) by COMPUTE!'s Gazette January 1988 magazine issue, and also the corresponding floppy disk subscription

This is the previously unpublished source code written by me (David R. Van Wagner) in 1987

## Instructions for building from source

1. Get a copy of [Fast Assember from COMPUTE!'s Gazette January 1986](https://archive.org/details/1986-01-computegazette/page/n79) or [FA+](https://techwithdave.davevw.com/2019/04/scrolling-editor-for-fast-assembler-31.html)*
2. Load/Run Fast Assembler
3. LOAD "SCRLEDIT.SRC",8
4. RUN
5. Will create SCRLEDIT program on disk 8
6. SYS 64738
7. LOAD "SCRLEDIT",8
8. RUN
9. See the original article for how to use

*Coincidentally FA+ is Fast Assembler plus Scrolling BASIC Editor built in August 1987

## Keystrokes

Key        |Description
-----------|-----------
F1         |Scroll up listing
F3         |Beginning of line
F5         |End of line
F7         |Scroll down listing
Ctrl+Down  |Bottom of screen
Ctrl+Ins   |Insert Line
Ctrl+Return|Toggle Scroll Edit Keys On/Off
