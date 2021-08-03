**Arduino** provides syntax highlighting and autocompletion for the Arduino programming language within the Nova IDE.


![](https://nova.app/images/en/dark/editor.png)

## Features

Arduino currently supports the following features:

- Code Highlighting
- Collections listed in sidebar:
  - Functions
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




## Support

For support / contributions / discussions please visit the [Github repository](https://github.com/DeeEmm/Arduino-Nova) or join us on [Discus](https://discord.gg/RHgrhZMuYH)

