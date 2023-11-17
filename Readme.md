# app básica para demostrar encriptar imagen en python 
The MIT License (MIT)

Copyright © 2023
email pcanelo@gmail.com
pcanelo www.studein.com

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files(the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge,publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS INTHE SOFTWARE.
## Step 1: Open terminal

## Step 2: Change the directory where are your app

cd xxxx

then execute 

```
python -m pip install --upgrade pipCopy
```
```
python -m pip install --upgrade PillowCopy
```
you can  use
```
pip install pycryptodome
```


## Step 3: Encrypt with ECB Mode
python encrypt_image.py -ecb Tux.png Tux_ECB.pngCopy
Open and look at the Tux_ECB.png file generated in the same directory

## Step 4: Encrypt with CFB Mode
```
python encrypt_image.py -cfb Tux.png Tux_CFB.png
```