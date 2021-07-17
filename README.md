# Calculator Application using Javascript
This is a simple calculator application that supports both clicking and key presses. The full list of supported keystrokes are listed in the [supported keystrokes](#supported-keystrokes) section.

# Preview
<p align='center'>
  <img src='https://user-images.githubusercontent.com/81805471/126028095-7435fbd1-6561-4ef2-8a06-9d8664551468.png' alt='Homepage'/>  
</p>

# Table of Contents
- [Preview](#preview)
- [Usage](#usage)
  - [Supported keystrokes](#supported-keystrokes)
- [Learning Points](#learning-points)
- [Contribute](#contribute)
  - [Adding new features or fixing bugs](#adding-new-features-or-fixing-bugs)
- [Feedback](#feedback)
- [License](#license)
- [Footer](#footer)

# Usage
Simply head to https://naduhz.github.io/odin-project-calculator/ to begin using the app! Alternatively, if you wish to host the project locally and make edits, you may clone the repository by doing:

```shell
cd your-directory-name
git clone https://github.com/naduhz/odin-project-calculator.git
```

and launching `index.html`.

[(Back to top)](#table-of-contents)

## Supported keystrokes
| Calculator Function | Corresponding Keystroke |
| ----------- | ----------- |
| All Clear | Backspace |
| Clear | Delete |
| Plus / Minus | _ |
| Square Root | \` |
| Decimal | . |
| Addition | + |
| Subtraction | - |
| Multiplication | * |
| Division | / |
| Equality | = |
| Numbers | 0 - 9 |

[(Back to top)](#table-of-contents)

# Learning Points
There were 3 main takeaways from this project:

1. Array methods
2. Handling of different data types
3. Keydown Events

Manipulating arrays was important for this project as I used them to act as the calculator's 'memory'. In this project, they were used to store the last entered operator as well as the two numbers to be operated on. Perhaps 1 thing I could have improved on in this project was to parse the 2nd number as a number literal instead of a string, which would have prevented a bulk of the code from looking like spaghetti code. However, not doing so also taught me the importance of being sensitive to data types especially since Javascript is not statically-typed. If I were to rewrite my code, I would probably have factored out common checks such as checking if the number is a decimal, or 0, into separate, globally and explicitly declared functions to prevent repetitive if/else statements and to make the code a whole lot more readable. Lastly, I learnt to use keydown and keypress events, and how to prevent the repeat event so as to prevent spam and to prevent the application from crashing.
 
[(Back to top)](#table-of-contents)

# Contribute
Please feel free to make any suggestions, edits or raise issues. Forks and pull requests are always welcome. I am not likely to maintain the code from here on as I have to move on to other projects.

[(Back to top)](#table-of-contents)

## Adding new features or fixing bugs
As mentioned above, I am not likely to maintain the code and as such, if you would like to build on this project, you could always fork or clone this repository.

[(Back to top)](#table-of-contents)

# Feedback
As this was done within a month of learning Javascript, the code is written in a very amateurish manner, so criticism is always appreciated with regard to how I can better write or refactor my code.

[(Back to top)](#table-of-contents)

# License
Project License can be found [here](https://github.com/naduhz/odin-project-calculator/blob/main/LICENSE).

[(Back to top)](#table-of-contents)

# Footer
I would like to thank [The Odin Project](https://www.theodinproject.com/) for providing the inspiration for this project.

[(Back to top)](#table-of-contents)
