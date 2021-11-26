# SudokuSolver

## Overview

Application is made to solve sudoku taken from camera or file

![IMG_0](https://user-images.githubusercontent.com/72568092/121086105-088e9e00-c7e3-11eb-9189-6b7cba0dc2d3.jpg)


Creating your own map of sudoku is also possible

![sudoku_created](https://user-images.githubusercontent.com/72568092/121086179-1e9c5e80-c7e3-11eb-8bb2-b0554449b4f9.jpg)

## Needed
- easyocr, opencv
- kivy, kivy_garden with xcamera
- numpy

## Description

Application with GUI with possibility to choose:
- algorithm to solve sudoku (2 algorithms)
- action mode (offline - taking photo in jpg, online - automatically showing solution as a camera preview
- creating own sudoku and checking, if it is valid (have only one solution)

## My contribution

- preparing algorithms solving and checking correctness of given sudoku board
- testing the foregoing algorithms
- constructing application's frontend
- in case of a problem we were discussing it together

## Conclusion
**Used or tested libraries:**
- Kivy
- Numpy
- Tesseract-OCR
- Pytesseract
- Easyocr

Unfortunately, finally we could not build an android app - it works correctly till we tried to detect sudoku in camera preview. The reason ultimately was lack of support to OCR libraries in Buildozer.
