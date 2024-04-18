# Testing
## Validator testing
* No errors were found on W3C CSS validator - [Apex MMA CSS validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fregan-boreland.github.io%2FApexMMA%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
* No errors were found on W3C HTML validator - [Apex MMA HTML validator](https://regan-boreland.github.io/ApexMMA/)
* I confirmed the contrasting colours is easy to read and the accessibility throughout the website is good. I did this by running the website through lighthouse.

![lighthouse](assets/images/readme-images/lighthouse-apexmma.png)

## Manual testing

### Fixed bugs
| Bug | Solution |
| ---| ---|
| favicon not loading | this was resolved by reviewing the favicon link and replacing the 'a' in assets from capital to lowercase |
| horizontal scroll on mobile phones and tablets | used a declaration to hide the overflow on the x-axis |
| header covering text main content on high resolution devices | used google chrome dev tools to adjust the resolution so I could view the change then adjusted the margin top to match the header size |
| form can be submitted without a first and last name | added an asset to the form declaration to make those fields required |

### Unfixed bugs 
* When rotating a mobile phone horizontal, the navigation doesn't fit into the header and navigation covers the text.
