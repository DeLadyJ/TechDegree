/******************************************
Treehouse FSJS Techdegree:
project 1 - A Random Quote Generator
******************************************/


# Tech Degree Project
My Pseudocode and RQG Code

//Create a variable quote array
//Get five quotes and put them in the quote arry with the source (citation and year) property
//Use console.log fuction to log to console

//Create a random number function that picks a number from 0 to the length of the array - this will create the array index numbers
//Create a getElementID string to get the quote 

//Create a HTML string that includes the quote and source (add citation and year if available)
//Create a print function to get the quotes and print them to the document
//Use the if stsement to check for the citation and year of the quote 

//Create a button that responds to an event listener when clicked and triggers the random quote generator

document.getElementById('loadQuote').addEventListener("click", printQuote, false);

// quote array
var quotes = (
  (quote, ('What God intended for you goes far beyond anything you can imagine.'),
  source, ('Oprah Winfrey'),
  tag, ('Insporational')), 
  (quote, ('There are still many causes worth sacrificing for/, so much history yet to be made.'),
  source, ('Michelle Obama'),
  tag, ('Inspirational')),
  (quote, ('Positivity/, confidence/, and persistence are key in life/, so never give up on yourself.'),
  source, ('Khalid'),
  tag, ('Life')),
  (quote, ('I always believed that when you follow your heart or your gut/, when you really follow the things that feel great to you/, you can never lose/, because settling is the worst feeling in the world.'),
  source,('Rihanna'),
  tag, ('Life')), 
  (quote, ('Don/’t worry about a thing/, /‘Cos every little thing is gonna be alright.'),
  source, ('Bob Marley'), 
  tag, ('Wisdom)
  citation, ('Three Little Birds/, from the album Exodus '),
  year, ('1977'))
  )

//log quotes array to console 
  console.log()

//Colors array
var colors = [
  'red', 'blue', 'green', 'yellow'
  ]


//calls a random quote
//calls a random color on a timer  
//then returns the quote

var randomNumber = Math.floor(Math.random() * quotes.length);

function getRandomQuote(){
  var randomNumber = Math.floor(Math.random() * quotes.length);
  return quotes(randomNumber); 
}
   
function getRandomColor(){
  var randomNumber = Math.floor(Math.random() * quotes.length);{
  setInterval("getRandomColr"),3000)
  return color(randomNumber);
}
 //setInterval("getRandomColr"),3000) 

 
  //document.getElementById('quoteDisplay').innerHTML = quotes[randomNumber]; 

    
document.getElementById('newButton'.addEventListener("click", function(){
  document.getElementById("clickButton").innerHTML (quote), (scr);
})


document.getElementById(quoteDisplayId):displayQuote; quotes[randomNumber]; HTMLElement





