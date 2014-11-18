My-LinkedIn-Page
================

My first Ruby on Rails and API experiment

"My LinkedIn Page" collects your LinkedIn data, and formats it from JSON to HTML. Hopefully, it will later save the information to a database and provide a link where anyone can access your page without authentication.

How to run the application locally
-----
1. Create a new LinkedIn API application on https://developer.linkedin.com/
2. Download my code
3. Create the files *apiKey.txt* and *apiSecret.txt* in the root, and add your API key and secret to the files
4. Start the application via typing `ruby s` in the terminal
5. Go to `localhost:3000/linkedin` in your favorite web browser.
6. Voilà!

Of course you can contribute to the project if you think it's a nice idea. You're also much welcome to provide feedback to marcus@marcusnygren.se.

Ideas:
-----
* Format the JSON data from the LinkedIn API into the format that JSON Resume uses, so that https://jsonresume.org can be used for generating the HTML page.
