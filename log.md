# 100 Days Of Code - Log

### Day 11: Jan 11, 2017 
**Today's Progress**: Completed basic commandline Tic-tac-toe application in Python. Still need to improve, but it's working in it's basic form!

### Day 10: Jan 10, 2017 
**Today's Progress**: Started with _Basic Algorithm Scripting_ assignments. So far completed:
* [Reverse a string](https://www.freecodecamp.com/challenges/Reverse%20a%20String?solution=%0Afunction%20reverseString(str)%20%7B%0A%20%20return%20str.split(%27%27).reverse().join(%27%27)%3B%0A%7D%0A%0AreverseString(%22hello%22)%3B%0A)
* [Factoralize a Number](https://www.freecodecamp.com/challenges/Factorialize%20a%20Number?solution=%0Afunction%20factorialize(num)%20%7B%0A%20%20var%20factorial%20%3D%201%3B%0A%20%20for%20(var%20i%3D2%3B%20i%3C%3Dnum%3B%20i%2B%2B)%7B%0A%20%20%20%20factorial%20*%3D%20i%3B%0A%20%20%7D%0A%20%20return%20factorial%3B%0A%7D%0A%0Afactorialize(5)%3B%0A)
* [Check for Palindromes](https://www.freecodecamp.com/challenges/Check%20for%20Palindromes?solution=%2F**%0A*%20Steps%0A*%20remove%20all%20non-alphanumeric%20characters%20from%20string.%0A*%20Split%20string%20into%20two%20equal%20parts.%0A*%20%20%20%20if%20given%20string%20is%20odd%20length%2C%20then%20leave%20character%20at%20the%20center%20and%20split%20string.%0A*%20Reverse%20second%20part%20of%20string%0A*%20Match%20with%20first%20part%20of%20string.%0A*%20If%20not%20matches%0A*%20%20%20%20return%20%22Not%20a%20Palindrome%22%0A*%20else%0A*%20%20%20%20return%20%22Yes%20Palindrome%22%0A**%2F%0A%0Afunction%20palindrome(str)%20%7B%0A%20%20var%20normalizedString%20%3D%20str.replace(%2F%5B%5E0-9a-zA-Z%5D%2Fg%2C%20%27%27).toLowerCase()%3B%20%20%0A%20%20var%20stringLength%20%3D%20normalizedString.length%3B%0A%20%20%0A%20%20%2F%2FDivide%20String%20into%20two%20equal%20halves%0A%20%20var%20splitIndex%20%3D%20Math.floor(stringLength%20%2F%202)%3B%0A%20%20%2F%2FStart%20of%20second%20half%20of%20string%20depends%20upon%20if%20input%20string%20is%20even%20or%20odd%20length.%0A%20%20var%20secondHalfStringStartingIndex%20%3D%20splitIndex%3B%0A%20%20%0A%20%20if%20(stringLength%20%25%202%20!%3D%3D%200)%7B%0A%20%20%20%20secondHalfStringStartingIndex%20%3D%20splitIndex%20%2B%201%3B%0A%20%20%7D%0A%20%20%0A%20%20var%20firstHalfString%20%3D%20normalizedString.substr(0%2CsplitIndex)%3B%0A%20%20var%20secondHalfReverseString%20%3D%20normalizedString.substr(secondHalfStringStartingIndex).split(%27%27).reverse().join(%27%27)%3B%0A%20%20%0A%20%20if%20(secondHalfReverseString%20!%3D%3D%20firstHalfString)%7B%0A%20%20%20%20return%20false%3B%0A%20%20%7D%0A%20%20%0A%20%20%2F%2F%20Good%20luck!%0A%20%20return%20true%3B%0A%7D%0A%0A%0A%0Apalindrome(%22eye%22)%3B%0A)
* [Find the longest word in a String](https://www.freecodecamp.com/challenges/Find%20the%20Longest%20Word%20in%20a%20String?solution=%2F**%0A*%20Split%20String%20using%20space%20separator%20into%20array%0A*%20for%20each%20element%20array%2C%0A*%20%20%20%20if%20length%20is%20greater%20than%20previous%20element%2C%20then%20treat%20that%20as%20longest%20word%0A*%2F%0A%0Afunction%20findLongestWord(str)%20%7B%0A%20%20var%20strArray%20%3D%20str.split(%27%20%27)%3B%0A%20%20var%20longestWordLength%20%3D%200%3B%0A%20%20%0A%20%20strArray.forEach(function(strElement)%7B%0A%20%20%20%20%0A%20%20%20%20if%20(strElement.length%20%3E%20longestWordLength)%7B%0A%20%20%20%20%20%20longestWordLength%20%3D%20strElement.length%3B%0A%20%20%20%20%7D%0A%20%20%20%20%0A%20%20%7D)%3B%0A%20%20return%20longestWordLength%3B%0A%7D%0A%0AfindLongestWord(%22The%20quick%20brown%20fox%20jumped%20over%20the%20lazy%20dog%22)%3B%0A)

### Day 9: Jan 9, 2017 
**Today's Progress**: Object oriented and Functional learning on FCC

### Day 8: Jan 8, 2017 
**Today's Progress**: Learning Basic Javascript on FCC

### Day 7: Jan 7, 2017 
**Today's Progress**: I think I've got working prototype for *Build a Personal Portfolio Webpage* project. Happy with progress so far.
**Link to work:** [FCC - Build a Personal Portfolio Webpage - Codepend Showcase](http://codepen.io/rkadam/full/QdbBPJ/)

### Day 6: Jan 6, 2017 
**Today's Progress**: Started work on *Build a Personal Portfolio Webpage* Project. Struggling with css. Gaining more understanding about Bootstrap 3 and how it makes life easy by providing components out of box.

### Day 5: Jan 5, 2017 
**Today's Progress**: Started working on *Build a Tribute Page* Project. Learning more about css, Bootstrap 3 framework, CodePen.
**Link to work:** [FCC - Build a Tribute Page - CodePen Showcase](http://codepen.io/rkadam/full/NdWVvg)

### Day 4: Jan 4, 2017 
**Today's Progress**: Completed first set of tutorials and now starting with Basic Front End development projects.

### Day 3: Jan 3, 2017 
**Today's Progress**: Starting freeCodeCamp. Going through inital tutorials.

### Day 2: Jan 2, 2017 
**Today's Progress**: Installed Sublime Text

**Thoughts**: I've heard lot of good things about this editor, started using it. Understanding how to install packages etc. Still lot to learn...

### Day 1: Jan 1, 2017

**Today's Progress**: Learn all about Z Shell and helper utilities like oh-my-zsh, z, trash 

**Thoughts** The more I know about Z Shell, the more I like it. It's really user friendly shell in my opinion. Things I like
* Using "tab" one can scan through list of options available for given command. Also you can use any arrow key to select the option you want to. Very fast!
* Write any command and then use arrow key to browse through history of it's execution.
* Themes from oh-my-zsh. I got "cobalt2" theme from https://github.com/wesbos/Cobalt2-iterm. Forked it, updated it's documentation to add more clarity. Created and successfully merged my Pull Request of 2017! Also made changes in forked version specifically for my needs.
* Gone through all (11 videos)[https://www.youtube.com/playlist?list=PLu8EoSxDXHP7tXPJp5ZmUpuT7sFvrswzf] from (Command Line Power User)[https://commandlinepoweruser.com/]. Very helpful videos to understand z shell.
