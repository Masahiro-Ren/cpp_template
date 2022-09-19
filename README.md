A cpp configuration template for building and running simple cpp programs on VScode

I use msvc as the compiler so that I don't need to install mingw and gcc or other things. (just for convinience).

Under the ``` .vscode ``` directory there are three json files
```
/.vscode
|- c_cpp_properties.json
|- launch.json
|- tasks.json
``` 
Just change ``` cpptest.exe ``` and ``` cpptest.cpp ``` in ``` launch.json ``` and ``` tasks.json ``` into your own filename. Then Ctrl + Shift + B build the project.