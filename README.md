# VisualBasic_FontAwesome [![Build Status](https://travis-ci.org/f-ewald/VisualBasic_FontAwesome.svg?branch=master)](https://travis-ci.org/f-ewald/VisualBasic_FontAwesome)

A simple project which creates a DLL file to use [Fontawesome](https://fortawesome.github.io/Font-Awesome/) (4.4) icons as labels or images in your VB.NET environment. Upon Build everything is included into a single DLL file. You can use any icon which is on the [CheatSheet](https://fortawesome.github.io/Font-Awesome/cheatsheet/) as an `Enum` as shown in the example.

## How to use
    Imports VbFontawesome.Fontawesome
    
    Public Class C
    
        Public Sub New()
            Dim fa = New Fontawesome()
            
            ' Assuming there is a label:
            
            ' Set the font first
            Label1.Font = fa.Font
            
            ' Get the character then
            Label1.Text = fa.GetIcon(VbFontawesome.Fontawesome.Icons.FaVideoCamera)

## MIT License
Copyright (c) 2015 Friedrich Ewald



Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:



The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.



THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
