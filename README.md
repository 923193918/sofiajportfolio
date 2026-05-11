Project 3- Sofia Yumiko Jacobs

# project overview
The goal of this project was to revise the website that we created for Project 1 to reflect what we have learned regarding website design so far. This project is meant to assess what we have learned regarding
- Correct Content (necessary pages, word count, etc.)
- Layout
- Navigation
- Responsiveness
- Cohesion
- Accessibility
- Understanding of the use of code for HTML & CSS
& Overall improvement of the website, compared to Project 1. 

For Step 1 of this project, I filled out the audit to get a general idea of what changes I needed to make for my website to meet all of the requirements, while also improving its readability, accessibility, etc. I created a wire frame, which I will add an image of below. 

For Step 2, I began creating the HTML and CSS of my website. I use previous knowledge from class sessions as well as my own research online to see how I could obtain the necessary changes I wanted to make. 

For Step 3, I began testing my website and seeing what looked best regarding colors, fonts, layout, boxes, images, hierarchy, etc. 

For Step 4, I moved my website from my desktop to GITHUB and made it a public website. 

For Step 6, I refined my website and began working on my README file, as well as my Written Reflection. 


# technical overview
My project is a multipage website that showcases some information about my interests to give insight into who I am as a designer. I built this site using HTML and CSS, with a little JavaScript for my Inspirations page (to make the navigation system turn into hamburger navigation: Responsive). My website goes from page to page through word links, which I have my navigation area in the header of every page (on the top right).  

General
For my header, I used an iframe to embed my GIF from the GIPHY website where I created it. I chose to have my gif appear on the left side of my header. I also included a navigation system, which would show up on the right of my header. 
I mainly used divs in my HTML in order to make styles in my CSS. Example: to make boxes for my text and image on my Home page, I added "div class="img-box", to add the img-box styling later into my CSS. I added hover-glow effects to all of my images to make them pop and match the girly theme that I had going. 

Inspirations page
I made my Inspirations page responsive. In order to do this, I added a little bit of JavaScript to the HTML. The JavaScript reads:    <script>
document.querySelector(".hamburger").addEventListener("click", function() {document.querySelector("nav ul").classList.toggle("show");});"
</script>"

I researched how to create the hamburger online. Based on my research, each section of JavaScript has a different function
- document.querySelector(".hamburger"): This code finds the first element in HTML that has hamburger as the class (which would be my navigation menu, since I want to hide it when it is on a smaller screen).
- addEventListener("click", function(): This allows the function to run when the hamburger element is clicked
- document.querySelector("nav ul"): This finds the navigation list (which contains the links to each page). 
- classList.toggle("show"): this activates the hamburger and shows the navigation menu

Top Fives
For my Top Fives Page, I decided to make the style decision to make two separate boxes on top of each other. Each box would contain 5 horizontal images with titles and captions underneath them. I chose this layout because I believe that it could efficiently hold the most information, while still being aesthetically pleasing. I used div classes to stylize the boxes in CSS and get each image to have a pink-glow hover effect, as well as the text. 

Trinkets
For my Trinkets Page, I decided to make this my page with the added movements (that I learned from Project 2). I decided to add the movements to the 4 images in the first box, which is titled "Sofie's Favorite Trinkets." I wanted to add effects that I thought matched each trinket. I styled each image's effect in CSS using keyframes. 

For example, I will break down how the keyframe for the Kewpie works. 
.four-item:nth-child(1) img:hover- This selects the box that the image is in, then selects the image, then makes the action occur when the mouse is hovering over the image. 
{
    animation: kewpieWiggle 0.5s ease; - Animation lasts 5 seconds, eases in and eases out
    box-shadow: 0 0 20px var(--accent); - Adds pink glow that I have for all of my images when I hover over them.
}

@keyframes kewpieWiggle- This creates the actual animation
{
    0% { transform: rotate(0deg) scale(1); } - Starting point
    25% { transform: rotate(2deg) scale(1.03); } - Tilts it right
    50% { transform: rotate(-2deg) scale(1.03); } - Tilts it left
    75% { transform: rotate(1deg) scale(1.03); } - Tilts right again
    100% { transform: rotate(0deg) scale(1); } - Returns to starting point
}


# acknowledgment
Overall, I am extremely proud of how my website turned out, and I think that my effort paid off. It was definitely difficult to make all of the different aspects of my website work correctly, but it was truly interesting to see all of my ideas come to fruition. I want to continue to learn how to build websites, especially for myself and others. 

Based on this project, I have shown that I am capable of: 
- Finding the weak points of my previous work
- Planning out the necessary changes needed to fix my work
- Research on how to make said changes & make them
- Explain how & why I made changes
- Create a usable website!

Websites I used for help:
- https://www.w3schools.com/cssref/css3_pr_flex-wrap.php
- https://www.syncfusion.com/blogs/post/css-flex-every-developer-should-know
- Microsoft Copilot


