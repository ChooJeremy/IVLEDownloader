# 11 Apr 2018

Windows release version:    
### [Download](https://github.com/denunciator/IVLEDownloader/blob/master/IVLEDownloader.exe?raw=true) 

Get the original from [here](https://github.com/yyjhao/IVLEDownloader/releases/tag/V1.1) and overwrite with the above .exe file.

See https://github.com/yyjhao/IVLEDownloader/issues/14 for context.


# Overview

This is simple Qt daemon to automatically download [National University of Singapore](http://www.nus.edu.sg/)'s
[Integrated Virtual Learning Environment](http://ivle.nus.edu.sg/) workbin files.

You can read more about it [here](http://yjyao.com/2012/08/nus-ivle-downloader.html).

---

# How to use?

In order to compile the source code, You will need the Qt SDK 5.0+, which can be found [here](https://www.qt.io/download).

Do download Qt SDK 5.5 or below, as Qt 5.6 updates WebKits to WebEngines, and this project requires WebKits. If you download Qt SDK 5.6 and above, you will need to [install WebKit yourself](https://forum.qt.io/topic/76739/webkit-status-2017)

If you want to fork it into your own app, you may consider changing the APIKEY in the .pro file.

