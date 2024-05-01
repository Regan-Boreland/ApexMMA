# Testing
## Validator testing
* No errors were found on W3C CSS validator - [Apex MMA CSS validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fregan-boreland.github.io%2FApexMMA%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
* No errors were found on W3C HTML validator - [Apex MMA HTML validator](https://regan-boreland.github.io/ApexMMA/)
* I confirmed the contrasting colours is easy to read and the accessibility throughout the website is good. I did this by running the website through lighthouse.

Lighthouse homepage on mobile phones:

![Lighthouse homepage on mobile phones](assets/images/testing-images/apexmma-home-(mobile).png)

Lighthouse gallery on mobile phones:

![Lighthouse gallery on mobile phones](assets/images/testing-images/apexmma-gallery-(mobile).png)

Lighthouse contact us on mobile phones:

![Lighthouse contact us on mobile phones](assets/images/testing-images/apexmma-contactus-(mobile).png)

Lighthouse homepage on desktop:

![Lighthouse homepage on desktop](assets/images/testing-images/apexmma-home-(desktop).png)

Lighthouse gallery on desktop:

![Lighthouse gallery on desktop](assets/images/testing-images/apexmma-gallery-(desktop).png)

Lighthouse contact us on desktop:

![Lighthouse contact us on desktop](assets/images/testing-images/apexmma-contactus-(desktop).png)


## Manual testing

### Testing user stories
`First time visitors`
| Goals | How are they achieved? |
| :--- | :--- |
| I want to get information on a mixed martial arts club in my local area. | The Apex MMA website provides information on what kinds of lessons a user could participate in, The price of the lessons, when the lessons occur and the location of the gym. |
| I want the site to be responsive to my device and maintain good accessibility. | I have developed a website that maintains responsiveness and ensures that people with disabilities will be able to navigate the website. |
| I want a website that has easy to use navigation but also informs me what page I am viewing. | The website has a navigation section inside the header but it also uses an underlining feature that informs the user of what page they are on.  |
| I want to be able to contact the club if I would like any information that isn't on the website. | Apex MMA has a enquiry section on the "contact us" page that allows users to make contact with the club owners if they require extra information. |

`returning users`
| Goals | How are they achieved? |
| :--- | :--- |
| I want to be able to maintain contact with the club and remain informed about any changes to the club | The Apex MMA website has social media links in the footer that allows users to remain in contact with the club. | 


### Full testing
The website was tested on the following devices:
* Iphone 12 Pro 
* Iphone 14 Pro Max 
* IPad Air 
* IPad Pro
* ASUS Zenbook Duo

The website was tested on the following browsers:
* Google chrome
* Safari 
* Microsoft Edge

`Home page`
| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Home link in navigation/header | Loads homepage and unnderlines "home" link in header | Clicked "home" | Home page loads and underlines the page name | Pass |
| Gallery link in navigation/header | Takes user to gallery page and underlines page name in header | Clicked on "gallery" | Takes user to gallery page and underlines the page name in header | Pass |
| Contact us link in navigation/header | Takes user to contact us page and underlines page name in header | Clicked on "contact us" link | Takes user to contact us page | Pass |
| Facebook link in footer | Takes the user to facebook in a new tab | Clicked on Facebook icon in footer | Opened Facebook in a new tab | Pass |
| Twitter/X link in footer | Opens Twitter/X in a new tab | Clicked on icon in footer | Opens Twitter/X in a new tab | Pass |
| Instagram link in footer | Opens Instagram in a new tab | Clicked on Instagram icon in footer | Opens Instagram in new tab | Pass |
| Youtube link in footer | Opens Youtube in new tab | Clicked on Youtube icon | Opens Youtube in new tab | Pass |

`Gallery`
| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Home link in navigation/header | Loads homepage and unnderlines "home" link in header | Clicked "home" | Home page loads and underlines the page name | Pass |
| Gallery link in navigation/header | Takes user to gallery page and underlines page name in header | Clicked on "gallery" | Takes user to gallery page and underlines the page name in header | Pass |
| Contact us link in navigation/header | Takes user to contact us page and underlines page name in header | Clicked on "contact us" link | Takes user to contact us page | Pass |
| Facebook link in footer | Takes the user to facebook in a new tab | Clicked on Facebook icon in footer | Opened Facebook in a new tab | Pass |
| Twitter/X link in footer | Opens Twitter/X in a new tab | Clicked on icon in footer | Opens Twitter/X in a new tab | Pass |
| Instagram link in footer | Opens Instagram in a new tab | Clicked on Instagram icon in footer | Opens Instagram in new tab | Pass |
| Youtube link in footer | Opens Youtube in new tab | Clicked on Youtube icon | Opens Youtube in new tab | Pass |

`Contact Us`
| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Home link in navigation/header | Loads homepage and unnderlines "home" link in header | Clicked "home" | Home page loads and underlines the page name | Pass |
| Gallery link in navigation/header | Takes user to gallery page and underlines page name in header | Clicked on "gallery" | Takes user to gallery page and underlines the page name in header | Pass |
| Contact us link in navigation/header | Takes user to contact us page and underlines page name in header | Clicked on "contact us" link | Takes user to contact us page | Pass |
| Facebook link in footer | Takes the user to facebook in a new tab | Clicked on Facebook icon in footer | Opened Facebook in a new tab | Pass |
| Twitter/X link in footer | Opens Twitter/X in a new tab | Clicked on icon in footer | Opens Twitter/X in a new tab | Pass |
| Instagram link in footer | Opens Instagram in a new tab | Clicked on Instagram icon in footer | Opens Instagram in new tab | Pass |
| Youtube link in footer | Opens Youtube in new tab | Clicked on Youtube icon | Opens Youtube in new tab | Pass |
| Equiry form | All information is required to submit the form and upon submittion the form will respond with a congratulations message from the code institute | Tried submitting form without any information filled in, tried submitting with spaces rather than the required information, tried submitting with all information | Upon submitting with no information filled in, the form wouldn't allow submission. When the form was filled in with spaces rather than letters the form prompted that this information was required. When all the information was filled in correctly the form allowed submission and a congratulations message appeared from the code institute. | Pass


### Fixed bugs
| Bug | Solution |
| ---| ---|
| Favicon not loading | this was resolved by reviewing the favicon link and replacing the 'a' in assets from capital to lowercase |
| horizontal scroll on mobile phones and tablets | used a declaration to hide the overflow on the x-axis |
| Header covering text main content on high resolution devices | used google chrome dev tools to adjust the resolution so I could view the change then adjusted the margin top to match the header size |
| Form can be submitted without a first and last name | added an asset to the form declaration to make those fields required |

### Unfixed bugs 
* When rotating a mobile phone horizontal, the navigation doesn't fit into the header and navigation covers the text.
