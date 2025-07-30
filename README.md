# mental-health-awareness

## Table Of Contents:
1. [Design & Planning](#design-&-planning)
    * [User Stories](#user-stories)
    * [Wireframes](#wireframes)
    * [Typography](#typography)
    * [Colour Scheme](#colour-scheme)

    
2. [Features](#features)
    * [Navigation](#Navigation)
    * [Footer](#Footer)
    * [Home page](#Home-page)
    * [Other features](#Other-features)

3. [Technologies Used](#technologies-used)
4. [Testing](#testing)
5. [Bugs](#bugs)
6. [Deployment](#deployment)
7. [Credits](#credits)

## Design & Planning:

https://ui.dev/amiresponsive - add website here once deployed to get a screenshot.

### Main Purpose of Website
The core purpose of this website is to promote mental health awareness by providing easy-to-understand, beginner-friendly information in a calm, supportive, and well-organised online space. It aims to:

🧠 Educate visitors on common mental health issues and stress management techniques

🎯 Create a safe, welcoming environment where users feel supported and not overwhelmed

🎨 Present content in a clean, calming design, using HTML, CSS, and Bootstrap to enhance accessibility and emotional comfort

#### Target Audiences Identified 

1. Individuals Seeking Mental Health Information
2. Students and Young Adults
3. Caregivers and Family Members
4. General Public and Community Members

### User Stories

User stories shown in Github project: https://github.com/users/GurpritK/projects/4 


### Wireframes

![mobile wireframes](assets/images/readme-images/mobile-wireframes.png)
![tablet and desktop wireframes](assets/images/readme-images/other-wireframes.png)


### Typography

I looked for fonts with a calm characteristic, and a minimal, simple design. Anythign too cursive felt busy, and didn't fit the design aesthetic of calm, minimal and clean that I'm looking to implement. I used AI prompts for google fonts to fit this description, and decided on using the **Inter** font.

### Colour Scheme
 
Colors That Calm the Mind: What Psychology and Cognitive Science Reveal: https://blog.cognifit.com/colors-that-calm-the-mind-what-psychology-and-cognitive-science-reveal/

- Used AI to find a colour palette with the calming colours identified from the article:
    - Sky Blue #A3D5F7 - Main background, buttons, section headers
    -  Soft Sage Green	#B5D8B2	- Accent panels, quotes, navigation highlights
    - Warm Beige	#F5EBDD- Card backgrounds, hero image overlay
    - Misty Lavender	#DDD6F3- Icon fills, modal backgrounds, section dividers
    - Cool Gray	#F0F0F0- Base layout, footer, forms

- Adjusted suggested sky blue to a slightly different shade for better compatibility

![Compatible Colour Palette Screenshot](assets/images/readme-images/colour-conflict.png)

https://color.adobe.com/create/color-accessibility 


## Features:
Explain your features on the website,(navigation, pages, links, forms.....)
### Navigation
### Footer
### Other features
## Technologies Used
List of technologies used for your project...
HTML
CSS
Bootstrap
Github

### AI Use
Used Copilot AI to implement my hero image and make it responsive across different screens, with an animated moving 'immediate support' button to bring attention to this CTA. Generated my hero image on Microsoft Copilot.

Used Gemini AI to create my images for 'common mental health issues', focussing on creating nature photorealistic images to evoke calmness, and have a consistent nature theme throughout the page. Found Gemini AI was more effective at creating images in comparison to Microsoft.

## Testing
Important part of your README!!!
### Google's Lighthouse Performance
Screenshots of certain pages and scores (mobile and desktop)
### Browser Compatibility
Check compatability with different browsers
### Responsiveness
Screenshots of the responsivness, pick few devices (from 320px top 1200px)
### Code Validation
Validate your code HTML, CSS (all pages/files need to be validated!!!), display screenshots
### Manual Testing user stories or/and features
Test all your user stories, you an create table 
User Story |  Test | Pass
--- | --- | :---:
paste here you user story | what is visible to the user and what action they should perform | &check;
- and attach screenshot

## Bugs
List of bugs and how did you fix them
Navbar font set to black by default by inheriting bootstrap properties. Created more specific styling to target this, and change to brown. 

Issues with the dropdown for 'common symptoms' - when I opened up one dropdown, it would increase the spacing in the cards of the neighbouring cards. Used Copilot to identify the cause:
"Problems Identified:
Inconsistent Card Heights: When one accordion expanded, it made that card taller, shifting other cards"

Get Immediate Support CTA button and navbar icon positioning overlaps on smaller screens.

Navbar burger icon opens up menu on the left hand side of page for smaller screens, but the icon sits on the right.

## Deployment

#### Creating Repository on GitHub
- First make sure you are signed into [Github](https://github.com/) and go to the code institutes template, which can be found [here](https://github.com/Code-Institute-Org/gitpod-full-template).
- Then click on **use this template** and select **Create a new repository** from the drop-down. Enter the name for the repository and click **Create repository from template**.
- Once the repository was created, I clicked the green **gitpod** button to create a workspace in gitpod so that I could write the code for the site.
#### Deloying on Github
The site was deployed to Github Pages using the following method:
- Go to the Github repository.
- Navigate to the 'settings' tab.
- Using the 'select branch' dropdown menu, choose 'main'.
- Click 'save'.

## Credits
List of used resources for your website (text, images, snippets of code, projects....)
  - Code & Text Content
  
  - Media
  
  - Acknowledgment
    