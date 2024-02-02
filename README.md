# JDownloader proxylist generator

Using socks-proxy.net it builds a list of proxies able to be imported and ready to use for JDownloader

You need to download the code first:
[DOWNLOAD](https://github.com/masterofobzene/JDproxygenerator/archive/refs/heads/main.zip)

Then, with a CMD inside that decompressed folder (JDproxygenerator-main), install dependencies:
```
pip install -r requirements.txt
```

Then just execute it:

```
proxy-scrapper.py
```

your proxylist will be a file named 'proxylist.jdproxies' (a json file) that jdownloader understands.
As the list is dynamic, when you have burned all your proxies just replace the list with a new generated one. 
Happy Downloading!

This is a fork of stealthizer's jdownloader-proxy-generator: https://github.com/stealthizer/jdownloader-proxy-generator
