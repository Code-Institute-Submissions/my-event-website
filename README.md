# My Event Website

My website will allow to set up a wedding party.

Users will be able to share:

locations maps, invitation card, pictures, music/sounds,   
   and send receive messages between partecipants that will be sit at their table
   or with all guests ("all tables").
   
The idea is to have a space where everything that happens on your wedding party will be captured 
This way all guests can retrieve the contents later.

Moreover Groom and Bride will have tons of pictures and nice moments recorded.

## UX

My event website or Wedd'Up is for Groom Bride to set up their wedding party and guests to share contents.

In this first version, as a Guest I want to login into the Eventroom to get my invitation card.  
  In the same space I will find "all contents" and "your gallery" to store and retrieve all images, sounds and pictures 
  recorded during the party.  
  Also I will be able to send and receive messages and share on the fly maps, images, etc.   
  Not only between the guests assigned to my table but also with all the other guests.  
  Essentially I will participate togheter with other guests to a community   
  created by the Groom and Bride specifically for this date.  

My mockup should be visible here:  
*[Go to my mockup](https://balsamiq.cloud/svddr58/plz55db/r2278?f=N4IgUiBcCMA0IDkpxAYWfAMhkAhHAsjgFo4DSUA2gLoC%2BQA%3D "MyMockup")*  
I used Balsamiq free trial hence there is a chance it won't be accessible

## Features

1) _index.html:_ landing page - I created a logo which is linked to this page  
    you will see a navigation bar with "Home", also linked to same page, "Login" to surf the "eventroom" page,  
    and "Support", this will provide a mock "need help?" phone contact.   
    Also there is a link to "What is" currently linked to a page that will show a under construction sign   
    
    In this page is also possible to sign up which will bring you to "sign up" page  
    Sign up button will show "sign up with google" or "sign up with facebook" if hovered.  
    This behaviour is not included on smaller screens in which you can always see google and facebook options  
    
    There is a brief disclaimer a second section with examples of what you can share and a footer with dummy links
    The video embedded in "examples section" contains captions.  

2) *sign_up.html:* section has a form to sign up with GET HTTP method, this to avoid errors why surfing the project from its Github link   

3) _eventroom.html:_ will have a top center menu with 5 "buttons":   
    **these and all other buttons in the project are fully functional without Javascript.**  
    The feature used is a radio hack   
    -> input radio hidden behind a label allows to catch the :checked selector in CSS  
    these five buttons will show:   
    + Profile: 1 picture and 2 tables with mock data  
    + Guests: table with current guests and which table they are assigned   
            on big screens will show online status as well     
    + Invitation card: selected by default,     
        table with invitaion card and three links to share, print and download
        Currently you can download it.  
    + All Contents and Your Gallery: 3 tables with 3 folders one per contact type ideally linked to a gallery section.  
    
    Another button will be at the center of the page over the messanging section  
    Clicking the button this will change from "go to all tables" to "go to your table"  
    The feature used is a radio hack changing z-index on the first label to hide it behind the second  
    to mimic a javascript dinamic button.   
    
    The "dialog box" will show a mock version of a messanging section.   
    Guests names in darkgreen to show their online status.  
    
4) *under_construction.html* page to allow for a better user experience while still working on the project.

## Technologies Used

I solely used Html5, Css3, Bootstrap 3.3.7:

+ [Html5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5);
+ [Css3](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3);
+ [Bootstrap 3.3.7](https://getbootstrap.com/docs/3.3/getting-started/)

## Testing

+ html5: [Html W3C validator via input](https://validator.w3.org)  
+ Css3: [Css W3C validator via input](https://jigsaw.w3.org/css-validator/validator)  
    please note validator shown following error:  
    *URI : TextArea  
    257		Unknown pseudo-element or pseudo-class :focus-within*  
    :focus-within can be found [here](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-within)
+ tested responsivness on dev tools, IE and Edge as well

On a functionality level the only test has been:
 1. Sign up form:  
        1. go to Sign_up.html via sign up button on landing page  
        2. fill the form   
        3. submit and check if validation will return error if no email is present.

### Media

The photos used for this website are all copyright free (even for commercial use):  
websites providing media:   
+ [Stocksnap](https://stocksnap.io/),
+ [Pixabay](https://pixabay.com/),
+ [Pxhere](https://pxhere.com/)

Video in the landing page has been provided by *CodeInsitute* for this assignment.
