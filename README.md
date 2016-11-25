# im4java

Clone of im4java 1.4.0 source distibution found at the [im4java home page](http://im4java.sourceforge.net).

Patched to fix an issue where generated script code would sometimes miss a space when the preceding line is too long.

Building on macOS:

    export JAVA_HOME=$(/usr/libexec/java_home -v 1.6)
    make clean src jar
