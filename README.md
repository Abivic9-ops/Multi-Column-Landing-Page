# TogetherHub Community Landing Page
A modern and responsive community engagement landing page built with HTML, CSS, and JavaScript.

TogetherHub is designed to demonstrate how digital platforms can encourage community participation, collaboration, and social impact through an engaging user experience. The project combines clean design, responsive layouts, interactive user interface components, and modern front end development practices.
## Project Overview

TogetherHub is a multi section landing page that promotes community involvement and showcases how individuals, volunteers, and organizations can work together to solve local challenges.
The application focuses on delivering a visually appealing experience while maintaining accessibility, responsiveness, and performance.
The interface includes dynamic interactions, animated statistics, theme switching, testimonial sections, modal systems, form validation, and mobile friendly navigation.
## Live Features

### Responsive Navigation
The navigation system adapts across desktop, tablet, and mobile devices.
Features include:

Responsive menu layout
Mobile navigation drawer
Sticky navigation header
Animated menu transitions
Active navigation states

### Theme Management
The application includes a built in theme switcher.

Capabilities include:
Light mode
Dark mode
Automatic theme persistence

Local storage integration
Smooth visual transitions

### Hero Section
The hero section introduces the platform and encourages user participation.

Includes:
Primary headline
Supporting description
Call to action buttons
Trust indicators
Community statistics preview

### Community Impact Statistics
Animated counters showcase community achievements.
Metrics displayed include:
Active volunteers
Community projects
Lives impacted

Project completion percentage
Statistics animate when they become visible within the viewport.

### Community Workflow Section
The platform explains its process through a structured three step workflow.

#### Identify Real Problems
Community members highlight local challenges and priorities.

#### Collaborate And Act
Participants work together to create practical solutions.

#### Track And Celebrate Impact
Communities monitor progress and celebrate achievements.

### Testimonials
Community success stories are presented through testimonial cards.
Features include:
Community member profiles
Ratings display
Responsive testimonial layout
Interactive carousel controls

### Call To Action Banner
A dedicated section encourages visitors to join the community initiative.

Includes:
Primary engagement button
Community participation indicators
Volunteer highlights

### Footer System
The footer provides:
Platform links
Company information
Support resources
Social media placeholders

Newsletter integration support

## Interactive Functionality

### Sticky Header
The navigation bar automatically transitions into a fixed header during scrolling to improve navigation accessibility.

### Mobile Navigation Drawer
Provides a responsive navigation experience for smaller devices.

Features include:
Slide in menu
Animated menu icon
Background overlay
Automatic closing actions

### Theme Toggle
Allows visitors to switch between light and dark themes while preserving preferences across sessions.

### Modal Framework
Reusable modal architecture supports future enhancements and user interactions.

### Form Validation
Client side validation ensures accurate user input.
Supported validations include:
Required field validation
Email format verification
Submission feedback

### Toast Notification System
Interactive notification messages inform users about actions and form submissions.
Notification types include:
Success
Information
Warning
Error

### Animated Statistics Counter
Statistics increment dynamically when entering the viewport using the Intersection Observer API.

### Dynamic Content Filtering
Supports searchable and filterable content sections for improved user experience.

### Timeline Switcher
Interactive timeline components allow users to switch between different information views.

### Success Story Slider
Provides a smooth carousel experience for displaying community success stories.

### Testimonial Carousel
Enables interactive testimonial navigation on smaller devices.

## Technology Stack

### Front End
HTML5
CSS3
JavaScript ES6

### Libraries
Boxicons
Font Awesome
Google Fonts

### Browser APIs
Local Storage API
Intersection Observer API
Match Media API
DOM Events API

## Folder Structure

```text
project-root

│
├── index.html
├── style.css
├── main.js
│
├── assets
│   ├── hero-bg.png
│   ├── banner_background.png
│   └── additional project assets
│
├── favicon
│   ├── apple-touch-icon.png
│   ├── favicon-16x16.png
│   ├── favicon-32x32.png
│   ├── favicon.ico
│   └── site.webmanifest
│
└── README.md
```

---

## Key JavaScript Modules

### Navigation Module

Handles:
Sticky navigation
Mobile menu interactions
Responsive navigation states

### Theme Module

Handles:
Theme initialization
Theme persistence
Theme switching

### Modal Module

Handles:
Opening modals
Closing modals
Keyboard interactions
Overlay management

### Validation Module

Handles:

Email validation
Required field checks
Submission processing

### Notification Module

Handles:

Toast creation

Toast removal
Notification styling

### Statistics Module

Handles:
Counter animations
Viewport detection
Number formatting

### Filtering Module

Handles:
Search functionality
Category filtering
Dynamic content visibility

### Carousel Module

#Handles:
Testimonial navigation
Success story sliders
Indicator updates

## Design System

### Typography
Font Family
Poppins

Typography focuses on:
Readability
Visual hierarchy
Consistency
Accessibility

### Color Palette
Primary Teal
Accent Purple
Accent Blue
Accent Yellow
Dark Theme Colors
Light Theme Colors

### Layout System
The project uses Flexbox extensively to create responsive layouts and maintain consistent spacing throughout the interface.


## Accessibility Features
Semantic HTML structure
Responsive typography
Keyboard friendly interactions
Theme accessibility support
Clear visual hierarchy
Accessible navigation patterns
Focus state support


## Performance Optimizations
Efficient DOM manipulation
Viewport based animations
Reusable component architecture
Minimal dependency usage
Optimized event handling
Theme preference persistence

## Local Development

### Clone Repository

```bash
git clone https://github.com/Abivic9-ops/Multi-Column-Landing-Page.git
```
### Launch Application
Open `index.html` in your browser.


## Customization
You can easily customize:
Brand colors
Typography
Hero content
Statistics
Testimonials
Call to action sections
Navigation links
Theme styling
Community data
All styling variables are centralized within the CSS custom properties section located at the beginning of `style.css`.

## Author
Victor Mwendwa | Abivic9-Ops

## License
This project is available for personal, educational, and professional learning purposes.
