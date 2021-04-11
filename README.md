# gran0482_2.github.io
Description

When creating my website I wanted it to maintain a professional look and feel all throughout to help bring in potential work. 

I chose to go with 3 colours to avoid having too many colours present. I also decided to have one dark background colour and one light text colour to place it on a dark background. I chose one bright colour as an accent colour to bring attention to certain titles, call to action buttons, card backgrounds and hover states. 

I wanted to have one font in my site to maintain consistency and to avoid having too many fonts. I also wanted to choose a font that appeared friendly, was easy to read and had different font weights so that it would allow me to bold text or make it bigger if I needed to.

On my website, I wanted to choose images and digital artwork that I felt best represented who I am and best represent my skills. I chose to include a link to my portfolio because I wanted my website to be easy to navigate without too many pages. By including my portfolio it allows people to see more of my work within my website. 

Challenges

Challenge #1 Bootstrap Navigation Menu Problem
During production when I was testing my website for user-functionality I noticed that my drop down menu was not functioning properly. I first checked my code to make sure I didn't take out any bootstrap element that came with the navigation. Then I began to google how to fix the issue to see what possible errors I could have made. This gave me a few ideas of what to look at and try. I tried fixing the dropdown menu based on the tips I found in my google search. Those tips did not work and then I decided to put a new bootstrap element template in to see if it fixed the issue. It fixed the issue and I learned that when using bootstrap its important to have the <script></script> function in your page for the elements to work. 

Challenge #2 Helicopter Banner Image Re-sizing Problem
When I added the helicopter image as the banner image I wanted the helicopter to be visible at all times. Originally when the viewport size grew so did the helicopter image and only the blades were visible. To solve this problem I googled my issue and found a codepen that helped me understand the object-position property that I was looking for. Now when the viewport grows in size the helicopter is always visible within the banner.

Challenge #3 Card Text and Image Issue 
When designing my cards in the About page below the graphic design area I tried to have the text stay in one place when the viewport size grew. The text would not stay in the same place and would often go outside of the container I had it in. Also, a similar issue was happening with my images. I had to try and make all the images the same size and they would fit the container appropriately. Since I had a bootstrap template in place I decided to replace my cards with the prebuilt cards that bootstrap has. This allowed me to fix both my image and text issue so all the elements would stay the same size when resizing to mobile, tablet or desktop.

Challenge #4 Self Portrait Stretching Issue (About Page) 
During designing my about page I included a self portrait and when the viewport resized my image stretched in a vertical way. To work around this issue I had to set a fixed height and width to avoid this problem and it would look the same size in mobile, tablet and desktop. 

Challenge #5 About page section divider
When resizng the viewport the text would go outside of the container and I didn't want that to happen. To get around this problem I used a bootstrap grid and then set the parameters for small, medium and large screen sizes.

Challenge #5 side bar scrolling (About page)
During designing my about page I noticed that my photography images and grahic design work was going off the side of the screen creating a horizontal scroll bar. I did not want this to happen. To work around this issue I had to adjust my bootstrap grid size for small, medium and large screen sizes. 


Learning Outcomes
During the creation and production of my web portfolio I learned that it is very important to do a lot of testing to ensure your website is responsive for various screen sizes and works with different browsers to ensure that your website is fully functional for all users across all screen sizes and browsers. A second learning outcome is that when I set properties in my mobile styles they will be inherited by my tablet and desktop styles and if I want the behaviour to be different in these I need to overwrite these styles. I also learned that changing an element in my mobile styles can sometimes effect the tablet and desktop behaviour unexpectedly so I have to be careful of my styles. 

Frameworks and Libraries
Bootstrap - https://getbootstrap.com/
CSS Reset -  http://meyerweb.com/eric/tools/css/reset/ 

Fonts
Open Sans - https://fonts.google.com/specimen/Open+Sans?query=open+s

Iconmonster
Twitter Logo - https://iconmonstr.com/twitter-1-svg/
Instagram Logo - https://iconmonstr.com/instagram-11-svg/


