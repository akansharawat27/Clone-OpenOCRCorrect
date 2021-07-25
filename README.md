# Clone-OpenOCRCorrect

Clone of OpenOCRCorrect application with the implementation of bold/unbold, superscript and subscript feature.


# How to run the Code?

1. Add the Shobhika Font to Ubuntu from https://github.com/Sandhi-IITBombay/Shobhika/releases/ for reading Devanagari:

    * Download latest version zip.
    * Unzip the file.
    * Open otf files with Font Viewer.
    * Click Install on Top Right Corner.

2.  Install qt5:
    * $ sudo apt-get install qt5-default
3. Go to folder "FrameWorkCode", compile qpadfinal.pro and make:
    * $ cd FrameWorkCode
    * $ qmake qpadfinal.pro
    * $ make
4. Execute file qPad in folder "FrameWorkCode"
    * $ ./qpadfinal


# Issues/Challenges
1. App exits without any warning.

# Features
* Added Features-
1. bold/unbold option
2. superscript
3. subscript
