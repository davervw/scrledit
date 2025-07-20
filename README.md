# Scrolling BASIC Editor for Commodore 64 (Source Code) #

Article and binary program were [originally published](https://archive.org/details/1988-01-computegazette/page/n81/mode/2up) by COMPUTE!'s Gazette January 1988 magazine issue, and also the corresponding floppy disk subscription

This is the previously unpublished source code written by me (David R. Van Wagner) in 1987, now with some updates from 2025

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
C=+Up      |Scroll up listing
C=+Left    |Beginning of line
C=+Right   |End of line
C=+Down    |Scroll down listing
Ctrl+Home  |Bottom of screen
Ctrl+Ins   |Insert Line
Ctrl+Return|Toggle Scroll Edit Keys On/Off
Ctrl+Left  |Word** left
Ctrl+Right |Word** right

(Note: C=/Ctrl can be interchanged in some cases)

**Word = consecutive similar characters, skipping spaces and punctuation

* letters: screen codes 01-1A (and 41-5A when not graphics)
* punctuation: 00,1B-2F,3A-3F 
* numbers: 30-39 
* graphics: 40-7F 
* control/reverse: 80-FF 
