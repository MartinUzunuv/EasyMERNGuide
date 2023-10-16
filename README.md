# EasyMERNGuide
# 1 Basic HTML, SCC, JS
Oh yea just go and watch some videos or read https://www.w3schools.com/ . It's honestly that easy. You cannot tell me that you can't learn that by yourself. It's the most simple thing in the world of programming. ChatGPT can also help you.

# 2 Dive deep into CSS
Don't you DARE make non-responsive web sites!
## 2.1 Flexbox
Flexbox is an easy way to make complex positioning.
- Basic read this page as much as to understand it, open it as often as you need: https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- You can also play around with the flexbox palyground: https://flexbox.tech/

# 3 Dive deep into JS
## 3.1 Handle events
"document.getEementById("anyButtonId").onclick = function(){console.log("Button clicked")}" Look at this in depth and try to understand it. Use chatGpt and videos. Don't overdo it. 
## 3.2 The cool way to code
- if(1 > 2){console.log("yes")}else{console.log("no")} can be replaced by console.log(1>2?"yes":"no") .
- if(xxx){yyy} can be replaced by xxx && yyy
- array.map((something, i), ()=>{console.log(`${i} = `+ something)}) make chatgpt explain this one. I'm lazy.
- Learn how to use "...". For example newArray = [...oldArray, newElement].
- Your boss likes this way of writing code more. You will like it too. Trust me here.
## 3.3 Math
This part isn't really necessary but it will make you smarter, better programmer, better person, better human, better scientist, better friend, better citizen, better at anything + it makes you stand out. Learn how to work with <canvas> and how to draw on it. Canvas is an html element that acts like a painting canvas and you can color it with functions like .fillRect(...) .  Learn how to draw circles with cos and sin: for(let a = 0; a < Math.PI*2; a += Math.PI/20){context.fillRect(100+Math.cos(a)*30,100+Math.cos(a)*30,1,1)}. Make some cool fractals like the tree fractal.

# 4 NodeJS
NOdeJS is a way for you to run js outside the browser. It will run in the terminal.
## 4.1 Download
Go to https://nodejs.org/en and download the latest version. Important: There will be a checkbox for something like "download all required dependencies and something...". Click it! YOU NEED ALL THE DEPENDENCIES! Now wait a lot. sometimes it may require you to press buttons or something but go with it. Also keep in mind that it may take some time and could possibly look like your computer is crashing but it's ok. You will most likely see a blue terminal or something... Just wait patiently.
## 4.2 Get started
Create a file called "index.js" or something and just cd to it and type "node index.js" in your terminal. Before you run it add something like "console.log("running")" in it. Now in your terminal you should see "running"
## 4.3 Paths
To change directory type "cd folderInTheCurrentFolderName". To go one level above the current directory type "cd.." or "cd ../folderName" or for many "cd ../../name". Just look this up yourselve. 
## 4.4 Run and interrupt/stop program
run: `node index.js`
<br>
interrupt/stop: `ctrl+c` (like "Cancel")

# 5 npm
npm (Node Package Manager) is a way to install stuff to your project. 
<br>
Go to https://www.npmjs.com/ and fina a cool api to use.
<br>
A cool example is https://www.npmjs.com/package/say .  Now learn how to use it. It should allow you to use text to speach in nodeJS
<br>
Here i must mention that npm works only in nodeJS
<br>
To install a library type 
`npm install packageName` or `npm i packageName`
<br>
Ask GPT to explain it a little further
