+++
    #this is the "front matter" of the template of a project. It's the variables associated with the file
    #this portion is written in TOML (Tom's Obvious Minimal Language)
    
    title = "Lily's Logo"
    #replace takes the filename and replaces all hyphens with spaces so that when it appears on your page, it's using spaces. The filename is used in the URL and URLs can't have spaces so use hyphen in the filename.
    #title converts to title-case (using capital letters for principal words only)
    
    date = 2019-06-06T01:20:11-07:00 #the date the file was created

    
    shortDescription = "This logo was designed for a client named Lily. It was used on her YouTube channel (although inactive) as a profile and trademark."
    projectVideo = ""
    #Project video is just the unique part of the URL  
    # For example, if the link is https://vimeo.com/285189099 then the unique part is  285189099
    projectVideoType = ""
    #Enter "youtube" or "vimeo". You can add other video types as well by editing single.html 
    projectImage = "lily.png"
    #Enter the filename only. For example, "metropolis_album.jpg" 
    #This image should be saved in the project folder with the name of your project 
    showImageOnProjectPage = true
    projectImageAltText = ""
    #Alt text is the text that gets read by screenreaders for accessibility (typically for the visually impaired) 

+++

<body class="lily">
<section class="overview">
    <h2 class="sectionTitle">Overview</h2>
    <p>Tools: Adobe Illustrator</p>
    <p>Role: Art Director, Designer</p>
    <p>Deliverables: Logo design</p>
</section>

<h2 class="sectionTitle">Project Summary</h2>

This logo was designed for a client named Lily. It was used on her YouTube channel (although inactive) as a profile and trademark. The design of the logo is simplistic in style. The water lily design with its green leaves forms an “L” shape, representing the client’s name. 

Meanwhile, the circular border with a triangular indent emulates the shape of a lily pad, playing on the concept of the water lily that blooms in the center. The color palette consists of the client’s favorite colors (green and pink) and the pastel tones chosen creates a softer and more feminine aesthetic. 

</body>

<!--

a new line in markdown will not be displayed in the browser.
\
\
\ 
the lines above this line showed up because they started with backslash (NOT A NORMAL SLASH) \
  
*here's some "emphasized" text, which defaults to italics but you can make it anythign you want in css*
**here's some "strong" text, which defaults to bold but you can make it anything you want in css**

Below is a list
* asterisks make bullets
- hyphens make bullets
+ plusses make bullets
* you can choose!
-->