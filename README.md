**Dear Apple**,

You have been doing a great job with the community. Since you open sourced Swift, we have seen the language evolving a lot, we've been able to follow the progress in the language, let you know about the issues that we found, and contribute directly to the language.

However, we haven't seen a lot of improvements in the tools that we use to build apps using Swift and Objective-C. That has brought some frustration, and we've ended up creating our tools to improve the way we develop, build and test our apps. In some cases, reverse engineering is the only API that we have.


Some issues that we're frequently facing and ideas to address them are:

- When targets contain a lot of source files, small changes can cause Xcode recompiling the whole target again. That turns into hours of developers rebuilding their projects unnecessarily. One solution that some companies have adopted is breaking up these targets into smaller ones. Similarly, small changes can cause Xcode invalidating previous builds and rebuilding everything from scratch. Ideally, Xcode should better understand the dependencies in either the source and the project, and prevent unnecessary builds. 
- Although build settings can be configured using a `.xcconfig` file, the rest of the project settings are not very accessible. Introducing changes in the project setup is only possible by using Xcode or parsing the unaccessible project files. A more open configuration would provide developers with more flexibility defining how the projects get built.
- While running UI tests we need to communicate with the app process. To make it possible we need to appeal to our solutions, for example using HTTP servers that run during the application lifecycle. If `XCTest` provided communication APIs it'd, simplify the way we UI test nowadays.
- The stability of Xcode in projects with many targets, and where Objective-C and Swift have to interoperate is very bad. It stops recognizing the syntax, autocompleting code, recognizing other modules' APIs. A more stable Xcode would have a great impact in our productivity.

Every WWDC we cross our fingers to see improvements in the tools that we need to create app experiences. Since Xcode and the build tools are not open source, the only option we have is kindly asking you to hear us.

Signed,

[Xcode developers](https://docs.google.com/spreadsheets/d/1Ge3TF0McmkBPc4UaXuLOth64XJLp4-bK0IkoWKL7l-o/edit?usp=sharing)

**If you are a Xcode developer you can sign the [letter here](https://goo.gl/forms/mUCTfVSCWJ1PGo7z1)**

> This open letter idea is inspired in [GitHub's one](https://github.com/dear-github/dear-github).