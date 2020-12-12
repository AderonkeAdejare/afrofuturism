HTML:
The main content in my HTML files is information about Afrofuturism and its various forms. I put the information in main, section, and div tags to make it easier for me manipulate their CSS. I used data-aos within these tags so these elements would be animated.
I included various types of media in my website like photos and Youtube videos. For my 'Explore' Page there is a form that is linked to my application through the POST method.

CSS:
I chose the light blue to dark purple linear gradient for my background because I based it off of the cover of "War Girls" by Tochi Oyebuchi. I based my website's text and link colors around the cover of "Africanfuturism: An Anthology" edited by Wole Talabi.
I decided to make my navbar transparent to add a more natural flow to the site. I styled my content to be in a grid that had a div with text and an area for media (or more text). I used the AOS Library (Animate On Scroll) to make my text and media blocks
fade in or fade from various directions as the user scrolls down. I made some of my images's width either be 100% or auto based on what I thought would look best on the page.

Javascript:
I used inline Javascript in my layout file so I could use the animated CSS in all of the needed HTML files.  This didn't work if the javascript was in a seperate file (I tried) so I included it in the layout HTML file.

Python:
I copied my application.py file from the Finance application.py and altered the file as necessary. I kept the apology grumpy cat meme to notify me of any errors in my code as I went along. I created app routes for all of my pages.
For my Explore page which contains the quiz, I wrote the different question options as lists and returned them on the GET method. For the POST method, I created a session variable for each option type and assigned it to the request form,
which got user information from my form.  Within my results route, I assigned each session variable to another, easier to follow variable name.  I then compared these variables to the options in my list through if, elif, and else statements.
There's about 186 lines of code going through all the option combinations to return a unique result. However, if someone clicks 'Past' for the time period for the genres 'Africanjujuism' and 'Africanfuturism', it will result in an apology page saying
to try again because these genres do not dwell on the past.

Flask:
I used the Flask framework for this website and organized my files appropriately. I used it in my layout template and then extended my layout template in other files so I would not need to copy everything that stayed the same - the header, navbar, and linked CSS -
in every single HTML file. I also used it to populate the options in my quiz with the lists in my python file and then to show the unique results of the quiz on another page.