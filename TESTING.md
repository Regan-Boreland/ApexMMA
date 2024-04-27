# Testing
## Validator testing
* No errors were found on W3C CSS validator - [Apex MMA CSS validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fregan-boreland.github.io%2FApexMMA%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
* No errors were found on W3C HTML validator - [Apex MMA HTML validator](https://regan-boreland.github.io/ApexMMA/)
* I confirmed the contrasting colours is easy to read and the accessibility throughout the website is good. I did this by running the website through lighthouse.

Lighthouse homepage on mobile phones:

![Lighthouse homepage on mobile phones](assets/images/testing-images/ApexMMA%20home%20(mobile).png)

Lighthouse gallery on mobile phones:

![Lighthouse gallery on mobile phones](assets/images/testing-images/ApexMMA%20gallery%20(mobile).png)

Lighthouse contact us on mobile phones:

![Lighthouse contact us on mobile phones](assets/images/testing-images/ApexMMA%20contact%20us%20(mobile).png)

Lighthouse homepage on desktop:

![Lighthouse homepage on desktop](assets/images/testing-images/ApexMMA%20home%20(desktop).png)

Lighthouse gallery on desktop:

![Lighthouse gallery on desktop](assets/images/testing-images/ApexMMA%20gallery%20(desktop).png)

Lighthouse contact us on desktop:

![Lighthouse contact us on desktop](assets/images/testing-images/ApexMMA%20contact%20us%20(desktop).png)


## Manual testing

### User stories
| Goals | How are they achieved? |
| :--- | :--- |
| I want to get information on a mixed martial arts club in my local area. | The Apex MMA website provides information on what kinds of lessons a user could participate in, The price of the lessons, when the lessons occur and the location of the gym. |
| I want the site to be responsive to my device and maintain good accessibility. | I have developed a website that maintains responsiveness and ensures that people will disabilities will be able to navigate the website. |
| I want a website that has easy to use navigation but also informs me what page I am looking at. | The website has a navigation section inside the header but it also uses an underlining feature that informs the user of what page they are on.  |


### Full testing

### Fixed bugs
| Bug | Solution |
| ---| ---|
| favicon not loading | this was resolved by reviewing the favicon link and replacing the 'a' in assets from capital to lowercase |
| horizontal scroll on mobile phones and tablets | used a declaration to hide the overflow on the x-axis |
| header covering text main content on high resolution devices | used google chrome dev tools to adjust the resolution so I could view the change then adjusted the margin top to match the header size |
| form can be submitted without a first and last name | added an asset to the form declaration to make those fields required |

### Unfixed bugs 
* When rotating a mobile phone horizontal, the navigation doesn't fit into the header and navigation covers the text.
