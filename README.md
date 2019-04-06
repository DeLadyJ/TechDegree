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

/***
  Create the `getRandomQuote` function to:
   - Create a variable to store a random number 
   - Cse the random number to `return` a random quote object from the `quotes` array.
***/

//calls random number from 0 to betwee last array length
//than gets the random number / quote, puts the quote in the HTML 
// then returns the quote

function getRandomQuote()
  var randomNumber = Math.floor(Math.random() * quotes.length);
  return quotes(randomNumber); 

 
  //document.getElementById('quoteDisplay').innerHTML = quotes[randomNumber]; 


/***
  Create the `printQuote` function to: 
   - Call the `getRandomQuote` function and assign it to a variable.
   - Create a variable for the HTML string and set it equal to an empty string.
   - Use the HTML template in the instructions or the markup in the index.html file, AND 
     the random quote vairable to build your HTML string.
   - Add the quote and source section to the HTML string.
   - Use an if statement to check for the citation property before adding it to the HTML string.
   - Use an if statement to check for the year property before adding it to the HTML string.
   - Don't forget to close that final `p` tag.
   - Set the `innerHTML` of the `quote-box` div to the HTML string. 
***/

function printQuote ();{ 
  console.log('newQuoteButton');}
  
  document.getElementById(quoteDisplayId):displayQuote; quotes[randomNumber]; HTMLElement

/***
  When the "Show another quote" button is clicked, the event listener 
  below will be triggered, and it will call, or "invoke", the `printQuote` 
  function. So do not make any changes to the line of code below this 
  comment.
***/

document.getElementById('newButton'.addEventListener("click", function(){
  document.getElementById("clickButton").innerHTML (quote), (scr);
})

// Remember to delete the comments that came with this file, and replace them with your own code comments.

