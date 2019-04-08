/******************************************
Treehouse FSJS Techdegree:
project 1 - A Random Quote Generator
******************************************/


# Tech Degree Project
My Pseudocode

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
  source, ('Oprah Winfrey')), 
  (quote, ('There are still many causes worth sacrificing for/, so much history yet to be made.'),
  source, ('Michelle Obama')), 
  (quote, ('Learn to be quiet enough to hear the genuine within yourself so that you can hear it in others.'),
  source, ('Marian Wright Edelman')),
  (quote, ('I always believed that when you follow your heart or your gut/, when you really follow the things that feel great to you/, you can never lose/, because settling is the worst feeling in the world.'),
  source,(('Rihanna')), 
  (quote, ('Don’t gain the world and lose your soul/. Wisdom is better than silver and gold.'),
  source, ('Bob Marley'), 
  citation, ('Zion Train/, from the album Uprising'),
  year, ('1980'))
  )

//log quotes array to console 

  console.log()


//calls random number from 0 to betwee last array length
//than gets the random number / quote, puts the quote in the HTML 
// then returns the quote

function getRandomQuote()
  var randomNumber = Math.floor(Math.random() * quotes.length);
  return quotes(randomNumber); 

 
  //document.getElementById('quoteDisplay').innerHTML = quotes[randomNumber]; 



function printQuote ();{ 
  console.log('quote');}
  
  
document.getElementById('newButton'.addEventListener("click", function(){
  document.getElementById("clickButton").innerHTML (quote), (scr);
})


document.getElementById(quoteDisplayId):displayQuote; quotes[randomNumber]; HTMLElement





