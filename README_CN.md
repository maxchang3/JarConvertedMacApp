# Jar Converted MacApp (especially for Apple Silicon)
## TL;DR


我使用 dante-biase 的 [jar2app](https://github.com/dante-biase/jar2app) 转换了一些自己常用的 jar 软件为 `.app` 文件。 他们可以很好的在 arm/x86_64 的 macOS 下运行，使用你自身的 jdk（所以你必须自己先装好 jdk）。 在 release 里下载即可。

软件列表:
|App Name|Intro|
|-------|-----|
|[jd-gui](https://github.com/java-decompiler/jd-gui)|Java Decompiler|
|[LogiSim](http://www.cburch.com/logisim/)|Logic circuits simulator|
|[LogiSim-Evolution](https://github.com/logisim-evolution/logisim-evolution)|Logisim's evolution|
|StegSolve| CTF Steg problems' solver|

## 详细
在 macOS 下，优雅的运行 jar 文件的方式就是把他们打包成 app 文件，因此许多开发者都通过这种方式构建他们的 java 应用。

同时，也有许多简单的方式打包 `.jar` 文件，比如 [jar2app](https://github.com/Jorl17/jar2app) 和另一个同名的 [jar2app](https://github.com/dante-biase/jar2app).

第一个并不能原生运行在 arm 平台上，但是后者可以，因为他的原理十分简单，没有额外依赖特定平台的和打包的动作。

我常用的一些软件的维护并不是很积极，因此他们并没有 arm64的版本、或者必须运行在自带的 jdk 上（这意味着仍然要转译） 、或者是没有 `.app` 的版本。

因此，我使用 dante-biase 的 [jar2app](https://github.com/dante-biase/jar2app) 转换了一些自己常用的 jar 软件为 `.app` 文件。

尽管如此，我仍然建议你自己打包。这并不难，看一下 [jar2app](https://github.com/dante-biase/jar2app)的 README 就可以用一行命令实现。

一部分图标是我自己设计（准确说是拼装）的，大部分使用了[pixabay](https://pixabay.com/) 的素材。