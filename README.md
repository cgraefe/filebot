# FileBot
[![SourceForge](https://img.shields.io/sourceforge/dt/filebot/filebot.svg)](https://sourceforge.net/projects/filebot/files/filebot/)
[![SourceForge](https://img.shields.io/sourceforge/dm/filebot/filebot.svg)](https://sourceforge.net/projects/filebot/files/filebot/)
[![SourceForge](https://img.shields.io/sourceforge/dw/filebot/filebot.svg)](https://sourceforge.net/projects/filebot/files/filebot/)

## Build Instructions

How to build FileBot in a nutshell:

1. Install current [JDK](http://java.sun.com/)

2. Install [Apache Ant](http://ant.apache.org/)

3. Install [Apache Ivy "Plugin"](http://ant.apache.org/ivy/download.cgi) for Ant

4. Fetch dependencies through ivy:

```ant resolve```

5. Build fat jar:

```ant fatjar```
