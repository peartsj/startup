# startup

First modification in the readme file, from the terminal on my computer. It is interesting to me that this will all be shared across so many different
platforms.

This is now the modification from the github website. I was previously unaware that this was possible, editing outside Now lets see what happens in the case of a conflict in the commit from github and now the commit from the console. This is the resolution.

# Really big heading
## Middle sized heading
### Gradually decreases heading size  
##### Smallest size heading

**This is used to bold text**  
*italics*  
~~strikethrough~~  
**Bold and _nested_ text**  
***All bold and italics***  
<sub> whatever this thing does  
  seems intereting</sub>  
<sup> This is superscript  
  compared to subscript</sup>  
    
  >Quoted text  

I learned a *lot* about formatting here on github and things I never knew befgore about how to resolve conflicts in code.  
I've never run into that problem before personally, but it was definitely instructive because I definitely can see it happening in the future.  


18.221.53.194  
ssh -i SpencerP-KeyPair1.pem ubuntu@18.221.53.194  
  
**https://spennysite.click**  
  
I learned a lot from the simon application, lots about the interaction between different html applications  
It was really interesting to see how to add links to other html pages as well as outside websites.  
The rest just seemd like formatting notes which I've seen in other locations, but interesting nonetheless  
Overall I can see how this will eventually become the full fledged simon machine as we learn more and more about in this class.  
  
In the most recent Simon assignment, I had to become familiar with how to use bootstrap in a game application similar to the one that I'll be building. I think it seemed most helpful when trying to pick colors and make the application cohesive. I also think that the implementation of the header in the application was well done and very effective. I'd like to study the code more to understand how the css interacts with the html file, but I was glad that I at least understood part of it. Definitely reference back to this application when doing the css and desighn in my startup application. Since we will also have a high scores page onn our startup application, it will also be a great resource when building that, so make sure to reference back to it as well.  
  
  This most recent simon application (3/6) I was able to see how things were coming together. something I want to note was how the html changed slightly to call certain functions when a button is clicked, and how to run a script, specified at the end after the footer, by only one line. I also wanted to note the simplicity of the scores.js file, that it is not always necessary to use a lot of code to get a fully functioning product that looks nice and is efficient. The play.js was a little more complicated, but definitely a good resource to see how to use Javascript a little more freely to make things interactive like the simon application.  
  
@import url('https://fonts.googleapis.com/css?family=Quicksand'); is able to be used in CSS to load fonts from google  
flex: column reverse swaps the orientation of containers - Two lines, with the first line saying World and the second saying Hello  
padding - Puts space around the content of selected elements  
const f = y => ++y;  
console.log(f(3)) will increment the number passed as an argument, hence it will print 4  
  
<div> creates a division element  
  order of the css box model (outside in) - margin, border, padding, content
  let a = ['cow', 'rat', 'fish'];
  let b = a.filter(v => v.match(/A|f/i));
  console.log(b);
  ['rat', 'fish']
  
  same let a
  let b = a.reduce((a,v) +> [a,v].join(':'));
  console.log(b);
  cow:rat:fish
  
  let a = [1, 2, 3];
  let e = a.map(number => {
  return ('a' + number)
  }):
  console.log(e); ['a1', 'a2', 'a3']
  
  document.querySelector('p').addEventListener('mouseover', console.log);
  Adds a mouseover event listener to a p element
  
  What is the HTML tag for an unordered list? - <ul>
  
  Which of the following is not a valid Javascript function? function f(x) = {}
  Actual functions: const f = (x) => {}
 function f(x) {}
 const f = function(x) {}
  

Which of the these is not a vaild way to include Javascript in HTML? <javascript>1+1</javascript>
  Actual way to include: <script>1+1</script> <script src='main.js' /> <div onclick='1+1' />
  
  Valid JS object: { n:1 }
  What does the DOM textContent property do? Sets the child text for the an element
  Which html will create a valid hyperlink? <a href='https://c.com'>x</a>
  
  <div>other</div>
  <div class="header">BYU</div>
  Using CSS, how would you turn only the BYU text blue? div.header { color:blue; }
  
  Which of the following is valid JSON? {"x":3}
  The following console command makes a script executable: chmod +x deploy.sh
  Which is a DNS subdomain? c260.cs.byu.edu
  To point to another DNS record, you should use the following DNS record type: CNAME
  
  
Simon Notes 3/22:  
- Node.js was super useful in providing a service backbone that I don't need to entirely understand  
- Express was also useful, and even though I don't entirely understand how it fits into the system  
- index.js was a good resource to look through to understand the functions that are provided through  
- app.use and app.listen can both definitely be used in my startup application  
  
Simon Notes 3/24:
- username and password are simonsite and simonsitepassword
- database is super convenient and I love the UI
- love that I don't have to host my own database  
  
Simon Notes 3/27:
- simon does a perfect implementation of a login and database feature, that already works with the mongo servers
- I like how you can't move past the login without logging in and being registered
- I can use the other html fileas and js files to implement the same in my own startup file
- mongo is super easy to use here and makes a big difference  

  Simon Notes 3/29:
  - The peer proxy file is where the majority of the useful code from this Simon project is located
  - The webserver could be interesting for potential functionality with our trivia game
  - Having ongoing high scores could be super useful, or we could use it to just alert people who else is playing
  - Also use code found in play.js and other play files to implement the websocket work on a different page
  
  Simon Notes 4/18:
  - Using a React Framework seems to require an entire rework of the application to be useful and to see any benefit
  - Create a react template by running "npx create-react-app template-react" in the project folder
  - Convert js files to jsx files
  - Move template files, switch to react bootstrap, and populate App.jsx
  - Create view components, create the router, and convert to react components
  ![simonReactProjectStructure](https://user-images.githubusercontent.com/49263156/232924875-71c4622f-a362-4547-960a-e6e43feaa457.jpg)
  - React seems like a very useful structure to use with an application, but I feel like it would be better if used right from the get go, instead of needing to convert an entire application after already building a working product. I can see the usefulness but I would like to have built my startup application using it from the ground up. Overall its a very cool framework and if I ever do build a future application I will definitely start out using the React Framework.
  
  Startup Service deliverable Notes 4/18:
  - We added a lot of the functionality of the application with this version of our code
  - We specifically added the ability to pull new trivia questions from a helpful API and load them into the game whenever needed
  - We also added the database to our code to score highscores and and keep track of users. The leaderboard is now fully functional, the game can get new questions whenever needed, and it parses the data and randomly displays the answers. 
  - We also added peer proxy code to let other players know when others are playing and when they score. 
  - Aside from that, we just polished up everything else in the application and did our best to improve the experience of our application and allow for fun trivia competitions!
  
# React Notes
- Really cool to be able to return whole elements using js functions
- React also has a cool way of being able to easily update text to reflect other parts of the script. This would have been super helpful to have during parts of the trivia application we made
- I'm most impressed by React's ability to dynamically react to anything that happens in the application, with either color change, text change, or even entire element changes and that feels extremely versatile

# Final Notes
- Http status code :  1xx informational, 2xx success 200 ok, 3xx redirection, 4xx client error 400 bad request, 5xx server error
- Standard http headers: Content-type, Host, cookie, more
- Cookies allow a server to store data on the client
- Websocket enables peer to peer communication instead of client to server
- Purpose of JSX: To inject html into javascript, to componentalize your html, allow for composability of your html
- Fetch works front end or backend
- Linux Daemon: Exectues independent of a user, starts when a computer is rebooted, can fork other processes, PM2 is an example of one
