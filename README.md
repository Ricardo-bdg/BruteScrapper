


<img src="https://github.com/Neek0tine/Scrapper/blob/main/assets/1-01.jpg" alt="DaNg" width="800"/><br>

# What is it?
**HOW TO WEBSCRAP** is a joint repository of the three musketeers whose goal is just one: **Avoid anti-bot websites**, a last resort.

There are three main phases on anti-bot website difficulty. 
* ### Requests
The first one is the Requests phase. First, a web scrapper will try to do a requests using a standard requests library or urllib3 for those who are special. This mostly works nicely before 2015.
After 2015 however, the big sites usually just block requests and throw a 400 Error code or just a blank page at us. We forgive those who blocks requests but also gives us an API to use. For those who blocks requests that
and isn't giving a single endpoint of API, now that's what this repos is for.

* ### Selenium
The second phase is selenium phase. Back then selenium driver is really powerful. Scrapping with selenium back then is like bringing an 155mm L/39 calibre M777 howitzer to a pillow fight. An absolute overkill of a weapon.
However, sites now checks your browser fingerprints too?! What is this?! Why do you really oppose us? What did we do wrong? (Me personally did not send 10000 requests per second, but for those who did is probably at fault here)

* ### PyAutoIt - PyAutoGUI 
Okay, this is the last resort. If you can't control my browser, control my mouse. Move my mouse, press my browser, type the link I want to go, and manually-automatically copies all the info required. I'm not sure if this is a stone age technology
or an absolute breakthrough of an innovation. This feels like bruteforcing our way in, but anything for those sweet sweet datas amiright?

# Why did I make this?
You can only annoy someone so much until they snap and decided to create something like this. The idea behind this 
module is that we're using something similar as AutoHotKey, in this case PyAutoGUI. Then we just made a bunch of sequences
and arrange them into classes and functions that is similar to requests or urllib class structure for easier use.

Text gathering is done by using clipboard module, since PyTesseract is a heavy library and generally a hassle to use. 
The text gathered is mostly from page source that has been soup'd or a simple select all texts on the site, I surely am will make
a function that does exactly like that but in a more controlled way.

"How about nested links?" You ask? Simple. PyAutoGUI has this amazing feature that lets you get a coordinate of an image 
given that you give PyAutoGUI target image. Target image is gathered easily by using something as simple as snipping tool.

# Usage

### PIP
To install using pip, simply type this command:<br>
`pip install git+https://github.com/Neek0tine/BruteScrapperl.git@main`

### Examples
<img src="https://github.com/Neek0tine/Scrapper/blob/main/assets/examples.png" alt="DaNg" width="800"/><br>

## End-User License Agreement
As per the MIT License:

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
1. The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

2. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


## Authors


* [**Miaw** ](https://github.com/ricardo-bdg)
* [**SleepyCats**](https://github.com/FluffHound)
* [**Neek0tine**](https://github.com/Neek0tine)


## Contributing

Pull requests are welcome. For major changes, how-to, and in-depth explanation, please contact one of the authors.
## License
![PyPI - License](https://img.shields.io/pypi/l/PyCl)
<br>
This project is licensed under MIT License - see the [LICENSE](https://github.com/Neek0tine/BruteScrapper/blob/main/LICENSE) file for details
