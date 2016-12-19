# English Chinese Machine Translation (英漢翻譯程式)

## Introduction

This program is a very simple Machine Translation web page between english and chinese.

The project contains two dictionaries ( [e2c.js](e2c.js) and [c2e.js](c2e.js) ) with 20000 words.

The main program is a web page that contains only 100 lines of javascript code.

All you have to do is click [translator.html](translator.html) and type in the text box.

## Example

Chinese Input

```
一隻狗追一隻貓 , 我為你感到驕傲 . 我希望你一切順利
----------------------------
a 狗追 a 貓 . 我 am 驕傲 of 你 . May 上帝保佑你.
你可以交談 to 外國人 in 中文 by 學習英文文法.
你 do not have to 記住 單字 for 學習ing 英文.
不要告訴 me that 你有一百萬美元s.

```

English Output

```
one 隻 dog chasing one 隻 cat , i for you feel proud . I hope you everything smoothly 
---------------------------- 
A dog chasing a cat . I am proud of you . May god bless you . 
You can chat to foreigners in chinese by learn english grammar . 
You do not have to remember vocabulary2 for learn ing english . 
Do not tell i that you have one million dollar s . 
```

## Analysis

If you write in english syntax words (such as [the a to by in on at ing ed that may) and chinese vocabularies, the english user may understand your sentence easily.

The language with english syntax and chinese vocabularies is called 《English-in-Chinese》。

On the other hand, if you write in chinese syntax words (such as [的、了、在、再、又...]) and english vocabularies, the chinese user may understand your sentence easily.

The language with chinese syntax and english vocabularies is called 《Chinese-in-English》。

## 簡介

本專案是一個非常簡單的《英漢翻譯網頁》。

整個專案包含兩個大約兩萬字的辭典 ( [e2c.js](e2c.js) 和 [c2e.js](c2e.js) )。 

主程式是一個網頁，該網頁包含 100 行的 javascript 程式碼。

你所需要做的就是開啟 [translator.html](translator.html) 然後開始輸入文章就對了。

## 說明 

當您保留 a the to by in on at ing ed that may 等語法詞時，翻譯的結果英語使用者會比較容易看懂。

這種具有《英文文法與中文詞彙》的語言，我們稱之為《漢英語》。

相反的、如果您輸入那些保留中文語法詞，像是「的、了、在、再、又...」等等詞彙，並依循中文語法的話，那麼那些中文使用者將會比較容易看懂。

這種具有《中文文法與英文詞彙》的語言，我們稱之為《英漢語》。

## License (授權)

The english_chinese_machine_translation project is licensed in MIT license.

Copyright (c) 2013 ccckmit

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
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

