# ...just sports...

Lot of people would like to doo some sports and don't want to get caught up in boring routine of training or repeating always the same exercises, going to same places, doing all the same stuff ower and ower again.

Our goal is to connect people from one community to meet up and train/play all kinds of sports together. We play a variety of sports in diferent locations making it so interesting to come and have fun with people with the same goal.

Users of the website will be able to see our location and times wann we meetup, registering to our page user will get information on our next meetups or some tournaments wich they could join.

## Design

![Responsice Mockup](https://github.com/Wulle91/welovesports/blob/main/assets/images/amiresponsive.PNG)

### Colour Scheme

I wasn't aware there are sites taht can help with color pallets so i didnt use any, I wend wit simple black and white combination 

### Typography

I imported fonts from fonts google, 'fugaz one' and 'kelly slab'. 

Big titles are with fugaz one, i choused it because i thought i looks energetic and powerful and for rest of larger texts and messages.

I used 'kelly slab' because it looks clean and easy to read but still nevertheless powerful.


![4 w 4 u](https://github.com/Wulle91/welovesports/blob/main/assets/images/section.PNG)

[Google Fonts](https://fonts.google.com/)

### Imagery

I downloaded two pictures from google.

First one is hero image witch was for some sports commercial.

Second one is picture with different balls witch is used as background under our containers, just on the first page I covered the background with transparent black color because so it is easier to read and that first page has more textual content than the others.

### Wireframes

![Balsamiq](https://github.com/Wulle91/welovesports/blob/main/assets/images/sports.png)

I used Balsamiq to sketch my page with general idea how it's supposed to look like.

## Features 

- __Navigation Bar__

  - Cover image with diferent players center align is abow our nav bar with underlined Home witch shows us on witch page are we're currently on and by clicking it it takes us  
    on top of our homepage.

  - Other elements in nav bar are Locations and Join Us witch take us to other pages.

  - Navigation is in font similar to those used for energy drinks witch complements the pasion for spots.
         
  - Navigation tells clearly where we are and what content we cann find on our webpage. 

![Nav Bar](https://github.com/Wulle91/welovesports/blob/main/assets/images/navbar.PNG)

- __The landing page image__

  - The header shows the simple title ...just sports... followd by imperative message to respect your body and indications ther later on user cann find out what is it about.

  - The header shows its clearly for sports-only, profesional adult athletes indicates its not for kids.
            
  - Section provides all the information after first impression given in header.

![Landing Page](https://github.com/Wulle91/welovesports/blob/main/assets/images/header.PNG)

- __4 w 4 u Section__

  - In section is our main content with inrtiguing title 4w4u following by 4 sections with 4 w questions, why, what, who, where with small intro to explanation, each one  
    expands on hover and in every one are further information eventually givin the full information about all there is about our topic.
           
  - This section, gives all necessary information aobut our page and our goals. 

![4 w 4 u](https://github.com/Wulle91/welovesports/blob/main/assets/images/section.PNG)

- __Locations section__

  - Second page of our webpage is locations section with all locations where and wenn we meet and what we play.
             
  - Locations page has 6 boxes with locations and every box hat iframe google maps with exact location of meetup, it convenient to users in cars allowing them to find location fast in cases where they are driving.

![Locations Times](https://github.com/Wulle91/welovesports/blob/main/assets/images/locations.PNG)

- __Join us section__

  -  The join us page has a form to collect details from users so they can be a member and join us on trainings.
  -  Form collects the users name, surname, email, and year of birth.

  -  Its important to register because the trainings are for members only and members get information, such es if locations are changed or if we organize or participate in tournament or something of similar content.
           
  -  Next to form is one motivational video to convince the users witch are still not shure if they want to join us or not.

![Locations Times](https://github.com/Wulle91/welovesports/blob/main/assets/images/joinus.PNG)

- __The Footer__ 

  - In footer are our social media links to take our users on our social media sites where are reguraly posted pictures of our meetups and trainings.
            
  - Links are colored green on hover and all links open in new tab.

![Footer](https://github.com/Wulle91/welovesports/blob/main/assets/images/footer.PNG)



## Testing 


I tested this page in different browsers Chrome, Firefox and Edge.

I confirmed that this project looks good and functions on all standard screen sizes using the devtools device toolbar.

I confirmed that the navigation, header, locations, sign up, section and footer are all readable and easy to understand.

`Home Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites navigation links | Takes to other pages wen clicked | Clicked pages | Takes to other pages | Pass |
| Page links hover | Page links change color on hover | Hover over link | Colors change| Pass |
| Page links | Opens page wenn clicked | Clicked link | Opens other pages| Pass |
| Social media link hover | Social media links change color on hover | Hover over link | Color change | Pass |
| Social media link | Takes us to our socialmedia pages wenn clicked | Clicked on button | Opens social media page | Pass |
| 4W container | On hover wxpands and describes one the perticular W | Hover over | Expands and explanation slides in | Pass |
| Location links | Loction link open google maps with directions where to go | Clicked on links | Takes us to google maps with that location | Pass |
| Motivational video | Video from youtube with play/pause button  | clicked on play/pause | Video played/paused | Pass |

I confirmed that the form works: requires entries in every field, will only accept an email in the email field, and the submit button works.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official w3c validaor.
  [W3C validator home](https://github.com/Wulle91/welovesports/blob/main/assets/images/w3home.PNG)
  [W3C validator loacations](https://github.com/Wulle91/welovesports/blob/main/assets/images/w3locations.PNG)
  [W3C validator join us](https://github.com/Wulle91/welovesports/blob/main/assets/images/w3joinus.PNG)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://github.com/Wulle91/welovesports/blob/main/assets/images/jigsaw.PNG)

- Accessibility     
  - I confirm that colors and fonts are easy to read by running it trought lighthouse in devtools. [lighthouse validator](https://github.com/Wulle91/welovesports/blob/main/assets/images/peformance.PNG)

### Fixed Bugs

- I couldn't style reset and submit button than i notced that new code is beein overwritten by code above that more specific was, I added to id parent element id an it worked fine.
- Submit and reset buttons didn't work. Closing form tag was right after opening tag, i probably did copy/paste instead cut/paste.
 

## Deployment


- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From there click on Page
  - Once there the link of our homepage will be shown on top. 

The live link can be found here - https://github.com/Wulle91/welovesports


## Credits 

### Content 

- The icons in the footer are taken from Frot Awesome       
- Instructions how do flexboxs work on youtube  [Specific YouTube Tutorial](https://www.youtube.com/watch?v=JJSoEo8JSnc)
- I applied all I learned from code institute

### Media

- Motivational video on Join us! from youtube     https://www.youtube.com/watch?v=g031sw47JqA&t=249s       
- Hero image                                      https://forsports.at/web/image/8747/All%20players.jpg
- Background image                                https://images.shiksha.com/mediadata/images/articles/1415964511phpXeEhUM.jpeg 
- Location maps from google maps                  https://www.google.com/maps


