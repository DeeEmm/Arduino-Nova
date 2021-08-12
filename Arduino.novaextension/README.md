**Arduino** provides syntax highlighting and autocompletion for the Arduino programming language within the Nova IDE.


![](https://raw.githubusercontent.com/DeeEmm/Arduino-Nova/main/Arduino.novaextension/Images/editor.png)

## Features

Arduino currently supports the following features:

- Code Highlighting
- Collections listed in sidebar:
  - Functions
  - Class Methods
  - Structs
- ~~ Auto Completion~~ (Please note that support for auto completion is currently very limited)


## Usage

Function and struct collections are listed in the sidebar provided that they follow standard lexical grammar...

```
void myFunction() {
	doSomething();
}

void myOtherFunction() 
{
	doSomethingElse();
}

struct myStruct {
	int myInt = 1;
}

struct myOtherStruct 
{
	float myfloat = 1.1;
}
```


## Setting up your environment

![Nova-tasks](https://user-images.githubusercontent.com/3038710/129142040-6943fff2-4ae8-4e03-8202-9a5878927429.jpg)

To make the most from Nova and to be able to use it to build and transfer Arduino based C++ projects to your target device you need to set up your local environment so that it uses Arduino-CLI. This is a command line based version of the Arduino compiler - basically the Arduino Editor but without the GUI. After creating some project tasks within your Nova projects settings to trigger the compile and upload actions.

There's a quick run-through on how to do this in the Wiki - https://github.com/DeeEmm/Arduino-Nova/wiki

If you use ESP32 you will also find information on how to set up PlatformIO-CLI to handle SPIFFS file transfers from within Nova as well

## Support

For support / contributions / discussions please visit the [Github repository](https://github.com/DeeEmm/Arduino-Nova) or join us on [Discus](https://discord.gg/RHgrhZMuYH)

