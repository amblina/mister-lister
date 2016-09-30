###File List

Prints to CLI all files in a provided directory

Use the `-d` flag to specify a direcory

 ````node index.js -d=/Users/thomas/Downloads/testDirectory````


This will print a list of files and directories in a format resembling the output provided by `npm list`;

````
  /Users/thomas/Downloads/testDirectory
 └──┬ 📁  levelTwoDirectory1
 |  ├─── 📁  emptyDirectory
 |  └─── 📄  text1-1.txt
 └──┬ 📁  levelTwoDirectory2
 |  └──┬ 📁  levelThreeDirectory1
 |  |  └──┬ 📁  levelFourDirectory1
 |  |  |  ├─── 🗻  image4-1-1.jpg
 |  |  |  ├─── 🗻  image4-1-2.jpg
 |  |  |  ├─── 🗻  image4-1-3.jpeg
 |  |  |  ├─── 📄  text4-2-1.txt
 |  |  |  └─── 📄  text4-2-2.txt
 |  |  ├─── 🗻  image3-2-1.jpg
 |  |  └─── 📄  text3-2-1.txt
 |  └─── 📄  text2-1.txt
 ├─── 📄  text0-1.txt
 └─── 📄  text0-2.txt
 ````