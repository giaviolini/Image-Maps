# Image Maps and Navigation Bar Part 2
## What I Learned/Practiced
Assignmnet 0 of 00

This website combines parts of previous assignments and takes them a few steps further. I had to create a realtor website using an image map, a header, a footer, and a navigation bar. 

### Image Maps 
To create an image map of current home listings, I used the same generator as before. This time it went a lot smoother because I knew how and what I wanted to accomplish. I think if I were to do this assignment again I would also include an active hover to my CSS, so it would help the user understand where they are clicking. I didn't know exactly what I needed to do for that before, and any examples I found were much more complicated than I thought they would be. A lot of them used Java Script, which is something I was not comfortable using at the time of this assignment. So, I skipped that feature, but I will look at adding in the future. 

### Navigation Bar
For this nav bar, I used a background color on the page links to have the hover appear in a box. In CSS, I needed to target both the ```nav``` and ```a``` selector to change the links for different pages. 

ex. ```nav a:hover {background-color: #110309;}```

### Header and Footer
The header and footer gave me a lot of trouble. Using the CSS ```position: absolute```, I was not able to have the header and footer span the full width of the page without it also covering all the text, So, for the time being, I left it as it is and I will troubleshoot that later. 

### Inputs or Forms
For this website, I also included forms to help make the website look complete.

The HTML for the Input Element require two attributes, a ```<input>``` tag and a ```<label>```tag. The ```<input>``` tag is where you specify what type of input you are using. Input exapmples can be a text box, date, email (or `mailto:`), or a radio button. After specifying the type of input, you also need an ID and a name, which can all be similar. For example you can use 'text' for the type, 'lastnameID' for the id, and 'lastname' for the name. Each parameter needs to be between the opening and closting tages for ```<input>```.

ex. ```<input type="text" id="firstname" name="firstname">```

The ```<label>``` will hold the title for  the input. 

ex.```<label for="lastname">Last Name:</label>```  

*Important note, the label should go before the input when typing code 

ex.```<label for="lastname">Last Name:</label>``` 
```<input type="text" id="firstname" name="firstname">```

[Visit here](https://giaviolini.github.io/Image-Maps/)
