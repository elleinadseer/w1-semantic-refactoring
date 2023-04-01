# w1-semantic-refactoring

## Description

"Refactoring code to improve the semantic structure of HTML elements."
"Contains quality README file with description, screenshot, and link to deployed application."

Provide a short description explaining the what, why, and how of your project. Use the following questions as a guide:

- What was your motivation?
- Why did you build this project? (Note: the answer is not "Because it was a homework assignment.")
- What problem does it solve?
- What did you learn?

## Usage

Provide instructions and examples for use. Include screenshots as needed.

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative filepath, add it to your README using the following syntax:

    ```md
    ![alt text](assets/images/screenshot.png)
    ```

## Credits

List your collaborators, if any, with links to their GitHub profiles.

If you used any third-party assets that require attribution, list the creators with links to their primary web presence in this section.

If you followed tutorials, include links to those here as well.

## License

The last section of a high-quality README file is the license. This lets other developers know what they can and cannot do with your project. If you need help choosing a license, refer to [https://choosealicense.com/](https://choosealicense.com/).

Changes:

NTS: Changed name from "hero" to "banner" (formerly "banner-image").
    Moved image from CSS to HTML so I could add ALT (suggested by Jack Stockwell on Slack)
    Changed from section to img via Jack

Search engine section. 
        FIXED: This section formerly did not hold an ID.
        This caused a link break that prevented jumping to this section when text clicked in nav bar.
        Including ID fixed this issue.

    Lead generation section
   NTS: Is benefit lead a bad name for this class? Not clear enough? 
   Doesn't match the naming conventions used in the Search engine section
   Removing the benefit-lead section made the text black and removed space gap at the bottom.

   Changed previous H2 to H4 to order the headings sequentially.
    Looks the same as before

    /* .benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
} */

 /*
 Removed all the sections below and combined their purposes into the benefits. sections above */
/*
.benefit-lead h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-lead img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-brand img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px; 
} 
END OF BENEFITS SECTION*/
/*
.search-engine-optimization img {
    max-height: 200px;
}

.online-reputation-management img {
    max-height: 200px;
}

.social-media-marketing img {
    max-height: 200px;
}

.search-engine-optimization h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.online-reputation-management h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
} */

/*    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    color: #ffffff;
}

.online-reputation-management {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    background-color: #0072bb;
}

.social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    background-color: #0072bb;
}*/

-

If I try to add these aspects from the repeated tags below it doesn't work
    margin-bottom: 20px; ????? sort repeated code
    padding: 50px;
    height: 300px;
    background-color: #0072bb;

-

/* Do I need to change the names of the two below?
Having code tied to something as missable as an a href and paragraph tag seems weird*/

/* Makes paragraphs font size 16px.*/

-

/* A makes the nav links white.
CHANGED: originally this was just named 'A' and it was unclear where in the code this purpose was functioning. Made it more specific. 
Not sure if this was the right thing to do? Because all links no longer have a uniform style accross the website.*/

-

/* P was originally here */
.banner
    height: 800px;
    width: 100%;
    margin-bottom: 25px;
    /* background-image: url("../images/digital-marketing-meeting.jpg"); */
    object-fit: cover;
/*    background-size: cover; */

