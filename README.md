# Jar Converted MacApp (especially for Apple Silicon)
## TL;DR

I convert some jar applications to `.app` using [jar2app](https://github.com/dante-biase/jar2app) by dante-biase. 

They can work well on arm/x86_64 macOS with your own jdk(So you must install jdk by yourself). You can download them in release.

App lists:
|App Name|Intro|
|-------|-----|
|[jd-gui](https://github.com/java-decompiler/jd-gui)|Java Decompiler|
|[LogiSim](http://www.cburch.com/logisim/)|Logic circuits simulator|
|[LogiSim-Evolution](https://github.com/logisim-evolution/logisim-evolution)|Logisim's evolution|
|StegSolve| CTF Steg problems' solver|

## Detail
In macOS, the elegant way run jar file is packing it to an app file, since many developers build their java applications in this way.

Also, there are many simple way to package the `.jar` file like [jar2app](https://github.com/Jorl17/jar2app) and another [jar2app](https://github.com/dante-biase/jar2app).

The first one does not support arm natively, but the second one can build app without the problem which due to it's simple principle.

Some applications I am using are not maintained actively. So whether they don't have an arm64 version or they can't run with your own jdk or they don't have an `.app` version. 

Cause of that I convert these applications' jar file to app using [jar2app](https://github.com/dante-biase/jar2app) by dante-biase. You can download them in release.

For all that, I highly recommend you convert it by yourself. It's not so hard, just read [jar2app](https://github.com/dante-biase/jar2app)'s README for one line command.

A part of icons are "designed" (combined in fact) myself mostly using [pixabay](https://pixabay.com/).