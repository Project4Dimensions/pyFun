# pyFun bookmarks

Switching web browsers often involves exporting and importing bookmarks and
keeping these up-to-date. Some web browser bookmark managers also lack fields
for tags and notes.

pyFun bookmarks works with any modern web browser. Use it to create, retrieve,
update and delete bookmarks.

The Browse Happy website suggests suitable browsers.  
[`https://browsehappy.com/`](https://browsehappy.com/)

See [`bookmarks.py`](bookmarks.py).

   
Usage

Install Python3 and dependencies.

For Debian and Ubuntu Linux, open a terminal and type  
`sudo apt install python3 python3-pip python3-bottle python3-eventlet sqlite3`.

For macOS and Windows, download installers from the following websites:  
[`https://www.python.org/downloads/`](https://www.python.org/downloads/)  
[`https://www.sqlite.org/download.html`](https://www.sqlite.org/download.html)  

In macOS and Windows, open a terminal and type  
`pip3 install bottle eventlet`

For Android, install and open Termux; then type  
`pgk update`  
`pgk upgrade`  
`pkg install sqlite python3`  
`python3 -m pip install --upgrade pip`  
`pip install bottle`  
`pip install eventlet`

Open a terminal, cd to the pyFun folder and type    
`python3 -m bookmarks`

In a web browser, paste and go to this link:  
[`http://localhost:8118`](http://localhost:8118/)

To import Firefox bookmarks, read this file:  
[`bookmarks-json2sql.md`](bookmarks-json2sql.md).

   
Tested with following web browsers

Firefox 100.0 (64-bit)  
Google Chrome 101.0.4951.64 (Official Build) (64-bit)  
IceCat 68.4.2esr F-Droid  
Microsoft Edge 101.0.1210.47 (Official build) (64-bit)  
Safari 13.0.5  
Safari iOS version 10.3.3  
Web 3.36.4 (powered by Powered by WebKitGTK 2.36.0)

   
References

Hellkamp, Marcel. 2018.  
    “Tutorial — Bottle 0.13-dev documentation.”  
    Last updated December 15, 2022.  
    [http://bottlepy.org/docs/dev/tutorial.html][0].

[0]: http://bottlepy.org/docs/dev/tutorial.html

Popov, Dmitri. 2015.  
    “Python in a Bottle: Using the Bottle framework to build Python apps.”  
    *Linux Magazine* 174 (May).  
    [http://www.linux-magazine.com/Issues/2015/174/Workspace-Bottle][1].

[1]: http://www.linux-magazine.com/Issues/2015/174/Workspace-Bottle

Schnelle, Jochen. 2018.  
    “Tutorial: Todo-List Application — Bottle 0.13-dev documentation.”  
    Last modified December 15, 2022.  
    [https://bottlepy.org/docs/dev/tutorial_app.html][2].

[2]: https://bottlepy.org/docs/dev/tutorial_app.html
