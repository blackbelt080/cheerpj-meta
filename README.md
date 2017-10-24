<p align="center"><img src="https://github.com/leaningtech/cheerpj-meta/blob/master/media/cheerpj_logo_whitebg.png" width="300"></p>

# CheerpJ - Java to JavaScript compiler (Beta)
[![Gitter chat](https://badges.gitter.im/leaningtech/cheerpj.svg)](https://badges.gitter.im/leaningtech/cheerpj)
[![GitHub Issues](https://img.shields.io/github/issues/leaningtech/cheerpj-meta.svg)](https://github.com/leaningtech/cheerpj-meta/issues)
[![Live Demos](https://img.shields.io/badge/demo-online-green.svg)](https://leaningtech.com/cheerpj/demos/)

CheerpJ is a Java bytecode to JavaScript compiler, compatible with 100% of Java, which allows to compile any Java SE application, library or Java applet into a JavaScript application.

Main documentation link: <https://github.com/leaningtech/cheerpj-meta/wiki>

Main project link: <http://www.leaningtech.com/cheerpj>

What is CheerpJ?
------

<p align="center"><img src="https://leaningtech.com/cheerpj/images/cheerpj_visual_2.png" width="450"></p>

CheerpJ is constituted of three components:
1. The CheerpJ AOT compiler, an LLVM-based Java-bytecode to JavaScript compiler. This can be used to convert Java archives (e.g. .jar) or single .class files to JavaScript. The CheerpJ AOT compiler is available for Linux, macOS and Windows.
2. The CheerpJ runtime library, a full Java SE runtime in JavaScript that can be distributed in part or in full with applications converted with CheerpJ.
3. The CheerpJ on-the-fly Java-to-JavaScript compiler, a reduced JavaScript version of the CheerpJ compiler that can be distributed with applications converted with CheerpJ to enable dynamic features of Java such as reflection.

What is unique about CheerpJ?
-------
1. CheerpJ can convert 100% of Java including reflection and proxy class creation, with no manual intervention on the code.
2. CheerpJ works directly on Java bytecode, and does not require access to the Java source code.
3. CheerpJ has a full Java SE runtime, inclusive of Swing/AWT.
4. The JavaScript code generated by CheerpJ is highly optimised and garbage-collectible.
5. CheerpJ enables bidirectional Java-JavaScript interoperability. JavaScript libraries, as well as the DOM, can be called and manipulated from Java. Converted Java modules can be invoked from JavaScript.

Getting Started
-------
You can download CheerpJ beta for Linux, Windows and macOS at this address:
https://leaningtech.com/cheerpj/download/noncommercial/

To get started with CheerpJ, please refer to the following pages:
1. [Getting Started](https://github.com/leaningtech/cheerpj-meta/wiki/Getting-Started)
2. [Command Line Options](https://github.com/leaningtech/cheerpj-meta/wiki/Command-Line-Options)

Demos
------
Several demos of CheerpJ can be found at https://leaningtech.com/cheerpj/demos/

Bugs and Questions
-------
 
CheerpJ is currently in a public beta stage, and we welcome any feedback and bug report on it through our Issue Tracking.

You can also get in touch via our [mailing list][mail].

[mail]: https://groups.google.com/forum/#!forum/cheerpj-developers
