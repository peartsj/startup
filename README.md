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
