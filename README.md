# Table of Contents <a name="Home"></a>

1. [About the project](#About)
2. [Features](#Feactures)
3. [Site Structure, mockup and colour scheme](#structure)
4. [LUXURY VILLA FOR RENT IN ADDIS ABABA](#landing)
5. [Features Left to implement](#Features-left)
6. [Stake holders of the Website’s Interest](#Stake-holders)
7. [Resources used to complete the project](#Resources-used)
8. [Testing](#Testing)
9. [Deployment](#Deployment)
10. [Content](#Content)
11. [Media](#Media)
12. [Technologies used](#Technologies-used)
13. [Credits](#Credits)


# About the project <a name="About"></a>
Luxvillas is an Estate agent that promotes luxury villas for rent for its clients in Addis Ababa, Ethiopia through creation of dedicated websites that are optimised for search engine.

The target audiences are foreign nationals such as investors who do business in the country, diplomats working in embassies and the African Union which has its headquarter in Addis Ababa, Ethiopia.  These particular audiences require a reliable information in English as well as a property that meets their family needs including safety, security and uninterrupted water and electric supply. This website exactly provides that by presenting handpicked property that suites their family needs, in a language they understand.

![looks on tablet, desktop and mobile](/asset/images/screenlayout.jpg)
 
## Features <a name="Feactures"></a>
### Sticky responsive navigation bar
The sticky responsive navigation bar provides all anchor links to each section of the page including to the description of the property, specification, location information, a form to book a viewing appointment and to the footer. What makes this navigation bar useful is that it sticks to the top of the page as the user scrolls up making it easy to navigate to other sections or go back to the top. This is identical every time the user jumps to different sections. On a mobile version it changes to a toggle navigation bar button and a home button and expands only when the user clicks on the toggle button. Once the user clicks on a link it will hide the list but remains at the top of the page.

### The small banner across the top
This banner contains the logo as well us the monthly rental price of the property. I believe the rental price will save time for the wrong audiences as well as portraying honesty and transparency to the right audiences.  People want to have an idea of the rental cost and don’t want to waste their valuable time browsing, if the property is above their budget. 

### Looping picture slider/Carousel*
The looping picture slider contains multiple images of the property and displays sequentially while still allowing users to take control through the carousel control “next and previous” button to flick through the property pictures without opening a popup window. 

## Site Structure, layout mockup and colour scheme <a name="Structure"></a>
The site structure was created using ‘xmind’ mind mapping application before taking the information to Indesign to do layout mockup.

 ![Site structure](/asset/images/structure.png)


###### Wireframe/mockup
The mock up was done by using the Indesign grid system and using the margins, columns and gutter which concept really helped me to understand margins and paddings used in CSS. the layout of the website is based on the layout mockup, although I improved as I progressed in the project. 

 ![Layout mockup](/asset/images/mockup.jpg)

### Colour scheme
The colour scheme was picked from the villas gate and from the first image of the carousel. The colours I picked were not exactly pure black,  orange or maroon but I  wanted a colour that will create emotional response such as  excitement and passion and resampled to orange, black and maroon. According to the colour psychology “orange brings feelings of enthusiasm, excitement and warmth and when combined with black it’s like an illuminating spotlight in the pitch-black night. Orange is also used to draw attention in traffic lights and in advertising. Maroon is also associated with passion, love, ambition, courage, strength, warmth, and beauty.”

 ![Colour scheme](/asset/images/colour-scheme.jpg)

[ Back to Table of Contents](#home)

## LUXURY VILLA FOR RENT IN ADDIS ABABA  <a name="landing"></a>

### The landing page 
- The landing page contains the header which explains what this website is all about as well as the type of villa and its location.
- The small banner contains the Luxvillas’ logo as well as the monthly rental price for the property. 
The carousel/picture slider sequentially displays large images fitting the screen horizontally to grab the user’s attention. 

![landing page](/asset/images/home.png)
##  Description Section 

This is the most important part of the website which describes the type of property Luxvillas are promoting through the use of languages that would trigger emotional response. These includes the security feature which often concerns foreigners as well as reassuring them about electric supply which often gets cut off and affects everyone in the country. The content is also written with SEO in mind and is used in the header, title and meta tag keywords.

![landing page](/asset/images/description.png)

## Specification section 

The Specification section of the website is  uses icons to represent each feature of the property as well as describing each feature including the bedrooms, living room and jacuzzi giving them the full picture of the property.

![Specification](/asset/images/spec.png)



##  Location section 

The location section gives the potential tenant/user local amenities such as  transport services, shopping malls, schools, cinemas and parks to help them make a decision. 

![Location](/asset/images/location.png)


## Form to allow users to book a viewing appointment 

Each of the above sections are laid out in a way that would lead them to this section to create an enquiry and finally to rent the property. The form allows a user to enter their details and select a suitable date and time to book a viewing appointment. The form is using [Formspree](https://formspree.io/) API to submit the enquiry.  


![appointment booking form](/asset/images/form.png)


##  Footer <a name="Footer"></a>

The footer section contains the general contact details such as address and P.O. Box number.

![landing page](/asset/images/footer.png)

[ Back to Table of Contents](#home)


##  Features Left to implement <a name="Features-left"></a>


**Videos** 
- Videos to show all aspects of the property

**Photo gallery**
- Photo gallery

**A call button**
- As I did not put a phone number for SEO reason I would have included a call button if I had more time

**Social media profiles**
-Links to social media profiles

**Location map**
- Add a location map


[ Back to Table of Contents](#home)



## Stake holders of the Website’s Interest <a name="Stake-holders"></a>



**The owner of the property**
- The owners interest is to make sure the website is functional, accessible, aesthetically pleasing and SEO optimised to attract the right tenants

**The potential tenants**
- The potential tenants interest is to find all the information they need to make a decision , have genuine contents (description, images, specification, form’s to book an appointment to view the property) and finally good user experience.

**The estate agent (LUXVILLAS) who’s developing the website**
- My interest is both the villa owner’s and potential tenants’  interests being met as well as the website attracting potential tenants and leading them to conversion.

[ Back to Table of Contents](#home)



## Resources used to complete the project <a name="Resources-used"></a>


### Responsive navigation bar
- The responsive navigation bar was created using W3c and further modified. 

Original navigation bar from W3c used a:active background class applied to home page and I modified that to make sure the usability is not compromised. As can be seen in the image below the active link background is applied to whatever link the user clicks on.

![Navigation bar](/asset/images/navbar.png)



### Picture slider 

The picture slider/carousel was taken from Bootstrap and modified with contents.

![original and modified forms](/asset/images/afternoonshade.jpg)


### Responsive Appointment booking form 

This was created using W3c tutorial and further modified including adding the reset button, repositioning items, adjusting the padding and margins and changing colours to fit with the brand colour.


![original and modified forms](/asset/images/forms.jpg)

[ Back to Table of Contents](#home)


## Testing <a name="Testing"></a>


The website was continuously tested to make sure HML and CSS are valid as well as making sure the website is accessible. 


### HTML
- Stray end tag span: span end tag was open
- No “p” element in scope but a “p” end tag seen

The image below shows the validation test result

![CSS validation Result](/asset/images/css-val.png)




###  CSS
-No errors were found

![HTML validation Result](/asset/images/html-val.png)


### Accessibility
- 9 contrast issues were found and fixed by changing backgrounds and colours
1 alert - no page regions: this was fixed by changing divs to header, main, nav and footer section.

![accessibility test result](/asset/images/accessibility.png)



### Performance testing
- Image size was too big and I optimised using photoshop - There were 2 Brocken links after I optimised and uploaded due some typos and I fixed

The final test shows that the page will fully load in 552ms of a second. Please see image below. 

![Performance test result](/asset/images/performance.png)

[ Back to Table of Contents](#home)



## Deployment <a name="Deployment"></a>


- The The website was deployed to Github as (estate-agent-1) after vigorous testing and fixing.

**The process of deploying involved the following:**
- Login to Github
- Access the estate-agent-1 website from the top left dropdown menu
- Click on settings from the top right of the navigation bar
- Scroll down to ‘Github pages’ 
- Choose the ‘Branch master’ from the drop down menu
Finally ‘save’ and the permanent url created
Here is the permanent URL of the website 

 https://digitallywise.github.io/estate-agent-1/ 

![Deployment screen](/asset/images/deployment.png)

[ Back to Table of Contents](#home)



 
## Content <a name="Content"></a>


- Text content was written by myself
 - LUXVILLA typographic logo was done by myself 

[ Back to Table of Contents](#home)


## Media <a name="Media"></a>

- All photographs of the villa were provided by the owner
Location image directly linked to Bole, Addis Ababa area picture on unsplash.com

[ Back to Table of Contents](#home)


## Technologies used <a name="Technologies-used"></a>

- GitHub for hosting the project
- Gitpod for authoring/developing the project
- Bootstrap for responsive carousel
- W3c for Flexbox tutorials, responsive form and navigation bar creation and practice
- CSS validation service - to validate my code
- HTML validation service - to validate my HTML
- GTmetrix - for website performance test
- Wave web accessibility test tool - to test for accessibility
- Adobe Photoshop, Illustrator and indesign - to edit specification icons, image optimisation, and wire framing
 
[ Back to Table of Contents](#home)


## Credits <a name="Credits"></a>


I would like to thank my mentor Felipe Souza Alarcon who is genuinely kind and helpful throughout this project. I would also like all the student care, tutors and the whole team at the code institute for all the help they have provided me. 

Finally I would like to thank and acknowledge the platforms that provided me the resources used to allow me complete this project:


- Code Institute instructors - for all the LMS video lessons
- GitHub and Gitpd - for the platform
- Slack and the slack community - for the tech support
- W3c for the tutorials and their validating tools
- Adobe creative cloud - for the image optimisation, icon editing and wire framing tools
- Bootstrap - for the carousel
Google for all the searches I’ve made for resources 

[ Back to Table of Contents](#home)








