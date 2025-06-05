JavaScript Hello World Example :
     1) Created a new project directory called helloworld to store the HTML and JS files.
     2) Open the helloworld project directory in your code editor.we'll use VS code.
     3) Create a new .html file name index.html inside the helloworld project directory with the following code :
          <!DOCTYPE html>
               <html lang="en">
                    <head>
                         <meta charset="UTF-8" />
                         <meta name="viewport" content="width=device-width, initial-scale=1.0" />
                         <title>JavaScript Hello, World!</title>
                    </head>
                    <body>
                         <script>
                              alert('Hello, World!');
                         </script>
                    </body>
               </html>
     4) Right-click the editor and select “Open with Live Server”. VS Code will start a web server and open the index.html in the default web browser.

     How it works
     First, use the <script> element to insert JavaScript into the index.html file:
          <script>
               alert('Hello, World!');
          </script>
     Second, call the alert() function to display an alert on the web browser:
          alert('Hello, World!');
     
     Including an external JavaScript file
          1) Create a new directory in the project directory called js . By convention, we place the JavaScript files in a directory called js, which stands for JavaScript.

          2) Create a new app.js file in the js directory with the following code:

               alert('Hello, World!');
               Code language: JavaScript (javascript)
          3) Modify the index.html to include the app.js file before the body closing tag:

          <!DOCTYPE html>
               <html lang="en">
                    <head>
                    <meta charset="UTF-8" />
                    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
                    <title>JavaScript Hello, World!</title>
               </head>
               <body>
                    <script src="js/app.js"></script>
               </body>
          </html>


          How it works.

The following includes the app.js file from the js directory in the index.html file:

<script src="js/app.js"></script>
Code language: HTML, XML (xml)
In this syntax, we place the path to the JavaScript file in the src attribute of the <script> tag.

When the web browser encounters the <script> tag, it downloads the app.js file specified in the src attribute and executes the JavaScript file.

Summary
Use <script> element to include a JavaScript file in an HTML page.
Use alert() function to display an alert in the web browser.