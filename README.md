## X-Pipe

X-Pipe (short for eXtended Pipe) is a tool that enables a fast and an efficient data
transfer/exchange between all types of producers and consumers of data,
e.g. different file types, applications, programming languages, databases, technologies, and more.

In contrast to normal pipes, X-Pipe is format aware and application aware,
i.e. it recognizes common formats and technologies and adapts to them.
X-Pipe is essentially a smart pipe that can connect files, databases, programming languages, applications, and more
while seamlessly managing to translate the transferred data into the appropriate format representations.

More information can be found in the [Documentation](https://docs.xpipe.io/about).

### Installation

Note that X-Pipe is still in its alpha phase.
Many features that are listed in the documentation are either not yet implemented or might still be buggy.
Therefore, the main target demographic are early adopters and people interested in development.

All X-Pipe releases can be found on the [GitHub Releases page](https://github.com/xpipe-io/xpipe-app/releases/).
Complete installation instructions and a user guide can be found in the [X-Pipe Documentation](https://docs.xpipe.io/installation)

### Components

The X-Pipe project consists out of multiple code repositories that can be found on GitHub.
Most components are open source, for example:

- [X-Pipe Java](https://github.com/xpipe-io/xpipe_java): The core components of the X-Pipe applications,
  X-Pipe Java API library, and X-Pipe extension development APIs.
  
- [X-Pipe Docs](https://github.com/xpipe-io/xpipe_docs): The documentation for the X-Pipe project.

- [X-Pipe ModuleFS](https://github.com/xpipe-io/modulefs): A file system implementation to access
  the contents of Java modules in a unified way. This library is frequently used by X-Pipe.
  
- [X-Pipe FxComps](https://github.com/xpipe-io/fxcomps): A library that provides a new approach to
  creating JavaFX interfaces and offers a quicker and more robust user interface development workflow.
  This library forms the basis for the GUIs of X-Pipe.
