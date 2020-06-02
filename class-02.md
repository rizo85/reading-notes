# HTML Text, CSS Introduction, and Basic JavaScript Instructions

[Back to Home](https://rizo85.github.io/reading-notes/)

### HTML
Duckett’s HTML book speaks about text and the structure that organizes it in to the familiar and consistent styles end users will expect to have to better receive information.
Writing text on an html document is like having someone else write a letter for you: you need to be very specific because in your mind you might have a certain vision, but how is the person helping you put this out there (the browser) know where and how you want your words and sentences to go?

The answer comes down to **semantic and structural markup elements.** 

A structural markup will have the formation and presentation of specific text and their structure, while semantic markup is used to give more information about the text for technology to use while not intended to be used to structure the structure of the text being rendered on to the page, even if a browser does present it styled like it is a structural decision.  
An application on a tablet might be able to make up a heading look bigger than a paragraph (structural markup), but an accessibility reader would be able to emphasize text read out loud if the semantic markup tag <em> is used.

#### CSS

Cascade Style Sheets are what makes our pages look the way we want them to. 
From least prioritized to most prioritized styles: external style sheets are able to link to our html via the <Link> tag, the <style> tag references internal style sheets that can overwrite the linked external styles, and the inline styles are overwriting anything else but must be changed manually at great time consumption if the whole page is getting a style makeover.

While it seems that the html is being restructured when padding or margins, font-size and word spacing, and line height and text alignment, the changes are only visual, and the information on the page can either be more successful at engaging users if used correctly.

Rules of CSS styles are created between the selectors of the html elements targeted and the attributes that are to be changed within the specific targets. 
If the selectors and the syntax is not correct the styles will not render, and if the style attributes are not carefully calibrated to the end user’s screen, it could cause the information not render completely or at all.     

#### Javascript

**JS** tells our web aplications how to conduct operations within a certain set of instructions.

The <script> tag tells the HTML we have a javascript program that can be called on the document. The <link> tag can also be used to reference an external file dedicated to javascript. This separation between HTML and the JS is desirable so that we have modularizing between the two parts of our web builds and don’t have to worry about creating a problem that would render both the html and js of a given page unusable at the same time. 

When it comes to js, creating a flowchart is a way to understand how our code will navigate thru each given instruction of a program from start to finish. This makes it so that each fork on the process of the instructions of an application are addressed, and so every interaction will lead on to a predefined outcome. 

Several data structures are available in js for us to manipulate and compare information sotred in to variables. Once the variables are defined we can sort thru them and filter results with loops to reach desired interactions:
- We can use loops to sort variables.
- We can take html input and turn them in to variables. 
- We can take a collection of data and filter it using loops and operators.

[Back to Home](https://rizo85.github.io/reading-notes/)
