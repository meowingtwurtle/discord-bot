# Contributing
This discord bot is written by and for the people of the code() discord, join [here](https://discord.gg/hFnDQ2F).

### Getting Started

1. Fork and clone the repo. ![Fork](https://img.shields.io/github/forks/code-discord/discord-bot.svg?style=social&logo=github&label=Fork)
2. Open project in IDE of choice (IntelliJ recommended)

### Writing Code
- Comment your code, especially code that may be confusing to beginners
- Use 4-width tabs
- Place opening braces on same line
- lowerCamelCase variables and method names
- Method names should usually be a verb or verb phrase
- UpperCamelCase class names
- Fields should be declared before methods

***Example***
```java
public class ExampleClass {

	// Fields
	private int c;
	
	// Constructor
	public ExampleClass(int c) {
		this.c = c;
	}

	// This method returns a + b + c
	public int doSomething(int a, int b) {
		return a + b + c;
	}

}
```

### Making changes
- Make sure your code works (run tests)
- Make sure your code fits the (very simple) style guide above
- Commit messages should explain changes briefly
- Submit pull request when done with all changes
