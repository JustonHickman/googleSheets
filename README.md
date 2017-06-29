# googleSheets

Send data to google sheets with javascript

instructions
* Create a google form
* right click on the form page and inspect element (Alternatively you can view page source)
* `ctrl + F` `<form action=`
* copy the form element and its action attribute (inclusive of url)
* also copy the value of the name attribute inside the <input>. it should look like `entry.2044927072` (we'll need this later)
* Paste it in your html page
* in the form tag create an input and button. Ensure the input has an id and the button has onClick attribute
* create a javascript function that will handle the onClick event
* In the javascript function under `url:` this is the same url as the url in the action attribute `<form action=[this-url]`
* The last step is to get the name of your input. it should look like `entry.2044927072`. paste this under `data: {...`
