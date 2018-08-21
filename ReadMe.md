Overview
========

RadVcLib is collection of properties to make it easy to add a library to your project.

The propery includes targets to download and extract a zip file from the library's official website.

The property file also setup the include directory, library directory and libraries necessary to build your project.

Finally, the property file also copies the required dlls to your projects output directory.

Example
=======

Say you wanted to add SFML to "MyProject".

First add the SFML.props to "MyProject.vcxproj".

You can then download and extract the libraries using the command:
```
msbuild MyProject.vcxproj /t:Update
```

You should then be able to build and run "MyProject".
