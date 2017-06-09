# CheerpJ Applet Runner (Beta)

![cheerpj logo](media/cheerpj_logo_whitebg.png)

The CheerpJ Applet Runner is a Chrome Extension that enables Java applets without requiring a local Java installation or to install deprecated plugins. This extension is available at <https://chrome.google.com/webstore/detail/cheerpj-applet-runner/bbmolahhldcbngedljfadjlognfaaein>.
 
Since Java Applets have lost support on the majority of browsers, a tremendous amount of content, particularly in science and education, is virtually inaccessible. We aim at solving this problem by providing a solution to extend the life of Java applets on modern browsers.

What is the CheerpJ Applet Runner Extension?
-------
![cheerpj_applet_example_gif](media/cheerpj_applet_demo1.gif)

The CheerpJ Applet Runner Extension works by converting the Java Applet on the fly through CheerpJ.js, a minimal Java-bytecode-to-JavaScript compiler, directly on the browser, and linking it to the CheerpJ runtime environment.

Main project link: <http://www.leaningtech.com/cheerpj>

Please note that the first activation of the CheerpJ Applet Runner extension on an applet will lead to a one-time download of approximately 20Mb. Sunsequent uses will only download the applet content.

Using the CheerpJ Applet Runner
-------

Please feel free to try the extension on any applet you like. Here are a few examples:
* http://www.neilwallis.com/projects/java/water/index.php
* http://www.javaonthebrain.com/java/iceblox/
* http://www.schubart.net/rc/
* http://sites.math.rutgers.edu/~sontag/JODE/JOdeApplet.html


Bugs and Questions
-------
 
The CheerpJ Applet Runner Extension is in beta, and we welcome any feedback and bug report on it either through the Extension itself or on GitHub. **Currently, multiple-window applets and pages with multiple applets are not supported. Some AWT elements might also not render properly**. 
 
We aim at supporting as many Java applets as possible, and eventually Java WebStart applications.
