#  Ylva/Ulf Elhammer - Tattoo Apprentice Portfolio 

This project is a portfolio website for Seattle-based non-binary tattoo apprentice Ylva/Ulf Elhammer. Their mentor is [Jude Le Tronik](https://judeletronik.com), a well-known Queer tattoo artist and the owner of [Lilith Tattoo](https://lilithtattooseattle.com). All artists at Lilith have a personal website linked from the studio’s [Artists page](https://lilithtattooseattle.com/artists)—except Elhammer! This website will help grow both awareness of and interest in their work, as well as allow perspective clients to connect with them.

## Demo 

A live demo of the site can be found [here](https://itmemarg.github.io/MS1-elhammer/).

![Website demo](https://github.com/ItMeMarg/MilestoneOne/blob/master/assets/images/demo.png?raw=true)
This mockup was created using [techsini](https://techsini.com/multi-mockup/index.php).


##  UX

*  As a potential client coming from [Lilith Tattoo’s website](https://lilithtattooseattle.com), I want to get to know a bit about Elhammer. I want to see both a biography and a gallery of their work to decide if I am interested in working with them.
![About page](https://github.com/ItMeMarg/MilestoneOne/blob/master/assets/images/about.png)

*  As a potential client interested in working with Elhammer, I want to be able to contact them to set up an appointment/commission a piece of art.

This website was designed to complement the design and overall “feel” of [Lilith Tattoo’s website](https://lilithtattooseattle.com). To accomplish this, we committed to a black/grey color scheme with maximum white space. Initial [wireframes](../wireframes/milestone1.pdf) do not include features we added for better UX.

When choosing a font, we wanted to honor Elhammer’s Swedish heritage. We found Josefin Sans to feature as the sole font used on the website; as [Figma](https://figma.com/google-fonts/josefin-sans-font-pairings/) notes, it “reflects Swedish design.” To ensure usability, we set the “ylva/ulf elhammer” #navbar-brand, headings, and paragraphs to a weight of 300; we set the #navbar-menu to a bolder weight of 600. This design choice differentiates features without the need for an additional font type. 


##  Features

###  Existing Features

*  Carousel showing select pieces from Elhammer’s portfolio - brings in users’ attention immediately when landing on the site and allows them to see some of Elhammer’s work.
*  Contact form - the chosen questions/inputs are minimal enough to keep the user’s attention and make it simple to complete and send the form. This form is **not** yet active.
*  Portfolio gallery - allows users to initially see an overview of Elhammer’s work as smaller thumbnails. When selected, images enlarge in a modal. 
*  Fixed navigation bar and footer - offers quick navigation to other pages or Elhammer’s social media accounts.
*  Envelope icon on footer - brings the user to the contact page, allowing them the option to reach out at any point of their visit. 
*  “ylva/ulf elhammer” navbar brand - maintains name awareness throughout the user’s time on the website. 
*  burger button - collapsing the navigation bar on medium and smaller screens decreases visual overload and layout clunkiness. 

###  Features Left to Implement
*  Further editing of Portfolio gallery modal, particularily sizing; this requires more knowledge of JavaScript, which I have not yet acquired. :)
*  Separate contact pages for illustration and tattoo appointments with more detailed contact forms, as well as portfolio pages with more images.
*  The contact form will be developed as I gain back-end skills. 

##  Technologies Used

### Framework
1.  [Bootstrap 4.0.0](https://getbootstrap.com)
2.  HTML5	
3.  CSS
4.  [W3.CSS/JavaScript](https://www.w3schools.com/w3css)

###  Libraries 
1.  [Google Fonts](https://fonts.google.com)
2.  [Font Awesome](https://fontawesome.com)

##  Testing

This project was consistantly checked with Google Chrome Development Tools while during development. As the project wrapped up, it was checked on Safari browser both on Mac and iPhone. 

A few bugs that persist in this project:
*  Carousel on Index - a little "jump" happens on smaller screens. This bug [was supposed to have been fixed](https://github.com/twbs/bootstrap/issues/22420) in the latest Bootstrap update (4.4.4). Updating this project's Bootstrap stylesheets led to further bugs, so it was decided to stick with the older version for the time being. 
*  Portfolio modal image size - when selected, the pop-up is a bit too large and awkwardly positioned, leading to bad UX. With further JavaScript knowledge, this will be properly addressed to have a smaller and more centered pop-up. 
* Portfolio page footer and nav sizes smaller than other pages - after adding the modal and JavaScript script, the aforementioned elements shrunk in size. I tried changing these elements' sizes to % rather than rem, but did not have success. 

##  Deployment
This project was created on and can be run on GitHub Pages. 

##  Credits


### Content

All textual content was written by me. 

Any code snippits taken from elsewhere are credited within the code and are below:
*  [W3.CSS](https://www.w3schools.com/w3css/w3css_modal.asp) for modal element on the Portfolio page
*  [Bootstrap](https://getbootstrap.com/docs/4.0/components/carousel/) for carousel element on the Index page
*  [W3](https://www.w3schools.com/js/js_popup.asp) temporary pop-up JavaScript box redirecting users to communicate with Elhammer through Instragram until form is active
*  [mmtuts](https://youtu.be/kEf1xSwX5D8) wrote the neat favicon code, which I was directed to by @anna_ci


###  Media

All media used in this site was obtained from Elhammer’s [personal Instagram account](https://www.instagram.com/yelvis/) and [tattoo Instagram account](https://www.instagram.com/ylva.tattoo).

###  Acknowledgements

*  Brooklyn-based tattoo artist [Rosa Bluestone Perr’s portfolio website](https://bluestonebabe.com/) inspired the light-on-text, heavy-on-imagery content design.
*  Ylva/Ulf’s home studio, [Lilith Tattoo studio](https://lilithtattooseattle.com) inspired design and color choices.
*  [@anna-ci's "How to make a Kick-Ass first Milestone"](https://slack-files.com/files-pri-safe/T0L30B202-FL1APG8SW/milestone_1_part_1.pdf?c=1586896605-8e988cbd8fc198b0) series of posts were incredibly helpful.
*  [Algonquin Design](https://learn-the-web.algonquindesign.ca/topics/html-semantics-cheat-sheet/)'s cheat sheets offered immense reference help.
*  [W3Schools](https://www.w3schools.com/), particularly [their how-to sections](https://www.w3schools.com/howto/default.asp) helped me play around with options and see possibilities to figure out what frameworks could be best used for this project. 
*  My partner, Eric, and our two cats, [Virginia](https://twitter.com/MiltantModerate/status/1249902617880186885) and [Elliott](https://twitter.com/MiltantModerate/status/1249477542488113153), lovingly supported me during the entirety of this project. 
*  My mentor, Sindhu Kolli, offered invaluable advice and helpful critique throughout my time working on this project. Saying this project would not be finished without her guidance cannot be understated. :) 

