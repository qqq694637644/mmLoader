# mmLoader http://tishion.github.io/mmLoader/

Library used for loading dll module bypassing Window PE loader  

Last build status:

[![Build status](https://ci.appveyor.com/api/projects/status/uyat3s3g76crdbkp?svg=true)](https://ci.appveyor.com/project/tishion/mmloader)

mmLoader is used for loaing dll module from memory directly. It can bypass the windows system PE loader and load module into process  address sapce. Also it will process all the import tables and reloaction table.

1. Use mmLoader source code:
   - Just include the source files inyo your projects.

2. Use mmLoader static library
    - Build the projects and collect the static library file, then add reference to it in your projects.

3. Use mmLoader the shell code
   - Build project mmLoader-shellcode-generator then run it, collect the generated header file. 
   - Include the header file in your project
