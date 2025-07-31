# Mental Health Awareness Website

![Website Banner](assets/images/readme-images/responsive-screen-images.png)

**🌿 Live Website:** [https://gurpritk.github.io/mental-health-awareness/](https://gurpritk.github.io/mental-health-awareness/)

## Project Overview

A responsive, single-page website promoting mental health awareness with accessible information about common mental health challenges. Built with a focus on creating a calming, supportive digital environment.

### Core Objectives
🧠 Educate visitors on mental health issues and stress management  
🎯 Create a safe, welcoming environment that reduces stigma  
🎨 Design with accessibility and emotional comfort in mind  
🔗 Connect users with professional organizations and emergency support 

## Table of Contents

1. [Project Overview](#project-overview)
2. [Design & Planning](#design--planning)
   - [User Stories](#user-stories)
   - [Target Audience](#target-audience)
   - [Wireframes](#wireframes)
   - [Typography](#typography)
   - [Color Scheme](#color-scheme)
3. [Features](#features)
   - [Navigation](#navigation)
   - [Hero Section](#hero-section)
   - [Content Sections](#content-sections)
   - [Interactive Elements](#interactive-elements)
   - [Footer](#footer)
4. [Technologies Used](#technologies-used)
5. [Testing](#testing)
   - [Performance Testing](#performance-testing)
   - [Accessibility Testing](#accessibility-testing)
   - [Browser Compatibility](#browser-compatibility)
   - [Responsive Design Testing](#responsive-design-testing)
   - [Code Validation](#code-validation)
   - [User Story Testing](#user-story-testing)
6. [Deployment](#deployment)
7. [Known Issues](#known-issues)
8. [Future Enhancements](#future-enhancements)
9. [Credits & Acknowledgments](#credits--acknowledgments)

## Design & Planning

### User Stories

**Project Management:** All user stories are tracked and managed through GitHub Projects: [View Project Board](https://github.com/users/GurpritK/projects/4)


### Target Audience
- Individuals experiencing mental health challenges seeking reliable information
- People supporting friends or family members with mental health issues

### Wireframes
![Mobile Wireframes](assets/images/readme-images/mobile-wireframes.png)
![Desktop & Tablet Wireframes](assets/images/readme-images/other-wireframes.png)


### Typography
**Font:** [Inter](https://fonts.google.com/specimen/Inter) - Modern, highly readable sans-serif designed for optimal screen legibility and calming aesthetic.

### Color Scheme
**Research Foundation:** Based on "Colors That Calm the Mind: What Psychology and Cognitive Science Reveal"

![AI Suggested Palette Compatibility Testing](assets/images/readme-images/colour-conflict.png)

#### Final Color Palette
| Color | Hex Code | Usage |
|-------|----------|-------|
| **Sky Blue** | `#97C3FA` | Hero gradients, primary accents |
| **Sage Green** | `#B5D8B2` | Navigation highlights, accent panels |
| **Forest Green** | `#2d5a3d` | Headings, section titles |
| **Warm Brown** | `#654321` | Body text, buttons, primary content |
| **Light Gray** | `#f8f9fa` | Section backgrounds, card backgrounds |
| **Medium Gray** | `#666666` | Secondary text, descriptions |

**Accessibility Compliance:** All color combinations meet WCAG 2.1 AA standards with contrast ratios of 4.5:1 or higher for optimal readability.

![Final Website Color Palette](assets/images/readme-images/website-colour-palette.png)


## Features

The website follows a **progressive disclosure** design philosophy, presenting information in an approachable, non-overwhelming manner that gives users autonomy to explore content at their own pace.

### Navigation

**Sticky Navigation Bar**
- Fixed position for constant access to all sections
- Responsive hamburger menu for mobile devices
- Smooth scroll navigation with visual feedback
- Hover effects with subtle box shadows for enhanced UX

### Hero Section

**Calming Forest Backdrop**
- AI-generated misty forest scenery to evoke tranquility
- Responsive background image with optimized loading
- Semi-transparent overlay for improved text readability
- Prominent "Get Support" call-to-action button with animation

### Content Sections

#### 1. Common Mental Health Issues
- **Interactive Cards** with nature-themed imagery for visual calm
- **Collapsible Accordions** preventing information overload
- **Consistent Card Heights** for professional grid layout
- **Comprehensive Coverage** of anxiety, depression, stress, and bipolar disorder

#### 2. Stress Management Video
- **Embedded YouTube Content** for visual learners
- **Responsive Video Player** using Bootstrap's aspect ratio utility
- **Educational Focus** on evidence-based stress management techniques

#### 3. Quick Tips Gallery
- **Horizontal Scrolling Cards** for easy browsing
- **Color-Block Design** using calming green gradients
- **Bite-sized Information** for quick consumption
- **Mobile-Optimized** touch scrolling

#### 4. Emergency Support Section
- **High-Visibility Design** with emergency icon
- **Crisis Helpline Information** prominently displayed
- **Clear Visual Hierarchy** for urgent situations
- **Accessible Design** meeting emergency content standards

#### 5. Professional Organizations
- **Curated Resource Links** to UK mental health organizations
- **Logo Integration** for instant recognition
- **External Link Security** with `rel="noopener"` attributes
- **New Tab Opening** to maintain website session

### Interactive Elements

**Accordion Components**
- Smooth expand/collapse animations
- Consistent spacing and alignment
- Keyboard navigation support
- Screen reader compatibility

**Horizontal Gallery**
- Touch-friendly scrolling on mobile
- Visual scroll indicators
- Responsive card sizing
- Smooth scrolling behavior

### Footer

**Professional Branding**
- Copyright information
- Social media integration (placeholder links)
- Consistent styling with site theme
- Responsive layout adaptation

## Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic structure and accessibility |
| **CSS3** | Styling, animations, and responsive design |
| **Bootstrap 5.3.7** | Grid system, components, and responsive utilities |
| **JavaScript** | Interactive components and smooth scrolling |
| **GitHub Pages** | Website deployment and hosting |

**Design Tools:** Microsoft Copilot AI (hero image), Gemini AI (content/imagery), Google Fonts, Squoosh (compression)  
**Testing Tools:** Google Lighthouse, W3C Validators, Adobe Color, Chrome DevTools

## Testing

### Performance & Accessibility
![Desktop Audit Results](assets/images/readme-images/desktop-audit-score.png) ![Mobile Audit Results](assets/images/readme-images/mobile-audit-lighthouse.png)

**Optimizations:** Added `rel="noopener"` for security, compressed images, semantic HTML structure, WCAG 2.1 AA compliance

### Browser Compatibility
| Browser | Status | Notes |
|---------|--------|-------|
| **Chrome** | ✅ Passed | Primary development browser |
| **Safari** | ✅ Passed | iOS and macOS compatibility confirmed |

### Responsive Design
![Desktop View](assets/images/readme-images/desktop-view.png) ![Tablet View](assets/images/readme-images/tablet-view.png) ![Mobile View](assets/images/readme-images/phone-view.png)

### Code Validation
![HTML Validator Results](assets/images/readme-images/html-validator.png) ![CSS Validator Results](assets/images/readme-images/css-validator.png)

### User Story Testing

**Comprehensive User Story Validation:**
All user stories from the GitHub project board have been tested and validated against acceptance criteria.

![Project Board - Completed User Stories](assets/images/readme-images/user-stories-screenshot.jpeg)


## Known Issues

**Minor UI Inconsistencies:**
- Mobile hamburger menu icon appears on right, but menu expands from left (aesthetic only)
- Social media footer links redirect to login pages rather than specific profiles (placeholder implementation)

**Resolved Issues:**
- ✅ Fixed navbar text defaulting to black (Bootstrap inheritance)
- ✅ Fixed accordion expansion causing card height inconsistencies  
- ✅ Fixed CTA button/navbar overlap on mobile screens

## Future Enhancements

### Technical Improvements
- [ ] **Performance Optimization:** Implement lazy loading for images and content

### Future Features
- [ ] **Resources Hub:** Add a resources webpage with a book and podcast recommendations, along with more YouTube videos
- [ ] **Community Page:** Create a community page where users can sign up to join the community

## Deployment

Website deployed using GitHub Pages:


![Deployment Configuration](assets/images/readme-images/deploy-screenshot.jpeg)

#### Live Website
🌐 **URL:** [https://gurpritk.github.io/mental-health-awareness/](https://gurpritk.github.io/mental-health-awareness/)


**Deploying on GitHub**
1. Go to the Github repository.
2. Navigate to the 'settings' tab.
3. Using the 'select branch' dropdown menu, choose 'main'.
4. Click 'save'.

## Credits & Acknowledgments

### Content Sources
- **[Mind.org.uk](https://www.mind.org.uk/)** - Mental health statistics and information foundation
- **[YouTube Stress Management Video](https://www.youtube.com/watch?v=qUz93CyNIz0)** - Educational content
- **"Colors That Calm the Mind"** - Academic research for color psychology

### Tools & Resources
- **[Adobe Color](https://color.adobe.com/create/color-accessibility)** - Accessibility testing
- **[Coolors.co](https://coolors.co/)** - Color palette generation  
- **[Squoosh](https://squoosh.app/)** - Image compression
- **[Am I Responsive](https://ui.dev/amiresponsive)** - Responsive testing
- **W3C Validators** - Code validation

### AI & Media
- **Microsoft Copilot AI** - Hero image generation and responsive design
- **Google Gemini AI** - Content generation and nature imagery
- **Organization Logos** - From respective official websites
- **[Inter Font](https://fonts.google.com/specimen/Inter)** - Typography

#### Coding using AI
I leveraged AI throughout my development process to both implement new features and refine existing code. For instance, I would often use a core piece of code from a framework like Bootstrap and then apply AI to enhance its aesthetics or add new functionality.

A specific example of this was when I needed a horizontal slidebar to display a gallery of tips. After several unsuccessful attempts at coding it myself using resources from Bootstrap and YouTube, I turned to AI. I described my issue and asked it to convert my existing carousel slideshow into a scrollable horizontal slidebar, which it implemented perfectly without any issues.

Beyond major features, I also used AI for more routine tasks to increase efficiency. This included setting repeat attributes on HTML elements and consolidating CSS to remove duplicate code. I also used AI to perform a final cleanup of the project, which involved removing redundant code and combining repeated selectors in the CSS. By augmenting my workflow with AI, I saved a significant amount of time, giving me the freedom to experiment with different features and designs.

Finally, AI was an invaluable partner during the testing phase. I used Chrome Developer tools to pinpoint issues with the website's layout or features, and then I would simply direct the AI to the line of code that needed fixing. This allowed me to see the effects of the changes immediately and revert them if they weren't what I wanted, making the debugging process much faster and more intuitive.

### Acknowledgments
- **Code Institute** - Educational framework and project template
- **Bootstrap 5.3.7** - Responsive framework
- **GitHub Pages** - Hosting platform



    