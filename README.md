# Pictionary Cards Generator

I couldn't find a pictionary anywhere in the city, so I decided to print one myself. I wasn't going to type all those words and names manually into Photoshop though, so I made this - a pictionary cards generator written in Python 3, using the Pillow graphics library. In its current form, it generates 100 cards across 7 A4 international paper size sheets, ready to print.

## Requirements

Requires Pythong 3.x, [Pillow](http://pillow.readthedocs.org/en/latest/installation.html#simple-installation) and the [Hans Kendrick font](http://openfontlibrary.org/en/font/hans-kendrick).

## How to use

To use the default word list, navigate to your cloned repo directory and then place the Hans Kendrick font into `resources`. Then, just run `./generate` in the terminal. You may need to `chmod +x generate` to give the file permissions to execute. If you'd like to modify the words that appear on the cards, look in /word-lists/ and modify the text files.

## Extras
There's also a PSD of a board in `resources` that you can print to play the game. It fits on an A3 piece of paper.

## The final product looks like this
![Pictionary-like Board](http://dew.dangelov.com/dewdrops/DEW-53dbfb4ca46180.37194370.JPG)

## License
Copyright (C) 2014 Dino Angelov

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.