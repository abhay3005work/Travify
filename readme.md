# Travify - Modern Travel Website

Travify is a premium travel website featuring smooth animations, interactive elements, and a modern dark-themed design. The project showcases various front-end techniques and components to create an engaging user experience.

## Table of Contents

- [Overview](#overview)
- [Pages and Features](#pages-and-features)
- [Components](#components)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Customization](#customization)

## Overview

Travify is a multi-page travel website demonstrating modern web design techniques, including:

- Full-screen video backgrounds
- Smooth scroll animations
- 3D Earth globe for destination selection
- Interactive image carousels
- AI chatbot for travel assistance
- Newsletter subscription form

## Pages and Features

### Page 1: Homepage

- Full-screen video background
- Animated hero text
- Navigation header
- Custom scroll indicator
- Parallax effects

### Page 2: Destinations Globe

- Interactive 3D Earth globe
- Clickable countries/destinations
- Loading indicator
- Country information popup

### Page 3: Travel Experiences

- Image carousel showcasing destinations
- Testimonials from travelers
- Dark-themed design with particle effects
- Touch-enabled controls

### Page 4: AI Travel Assistant

- AI chatbot interface
- Responsive message bubbles
- Suggestion chips for common queries
- Travel information knowledge base

### Page 5: Newsletter & Connect

- Newsletter subscription form
- Social media links
- Success message with animation
- Form validation

## Components

### Custom Cursor

A custom mouse follower that enhances the interactive experience:

- **cursor-outer**: Larger circle that follows cursor with slight delay
- **cursor-inner**: Small dot that follows cursor precisely
- Features hover state expansion, click effect, and smooth transitions
- Automatically disables on touch devices

### Smooth Scrolling (Lenis)

Implementation of smooth scrolling across the entire site:

- Uses Lenis library for premium scroll experience
- Configurable speed and easing
- Synchronizes with GSAP animations
- Prevents conflicts with interactive elements

### Image Carousel

A responsive image carousel with modern interactions:

- Touch swipe functionality
- Automatic rotation with pause on hover
- Animated slide transitions
- Caption overlay for context
- Interactive indicators

### Frame Animation Scroll

A scroll-triggered animation that plays through sequential image frames:

- GSAP and ScrollTrigger integration
- Loads images progressively
- Synchronizes animation with scroll position
- Creates cinematic effect

### 3D Earth Globe

Interactive 3D globe for exploring destinations:

- WebGL-based 3D rendering
- Country detection and highlighting
- Information display on hover/click
- Smooth rotation and zoom capabilities

### AI Chatbot

A JavaScript-based chatbot that simulates AI travel assistant:

- No external API requirements
- Knowledge base of travel information
- Natural-looking typing animation
- Context-aware responses
- Dynamic suggestion chips

### Newsletter Form

A subscription form with validation and feedback:

- Form validation
- Success confirmation
- Social media integration
- Animated submission effects

## Technologies Used

- **HTML5/CSS3**: Modern markup and styling
- **JavaScript**: Interactive functionality
- **GSAP** (GreenSock Animation Platform): Advanced animations
- **ScrollTrigger**: Scroll-based animations
- **Lenis**: Smooth scrolling
- **Tailwind CSS**: Utility-first styling
- **Three.js**: 3D globe visualization
- **Google Fonts**: Typography
- **SVG Icons**: Vector graphics

## Installation

1. Clone or download the repository
2. Open index.html in a modern browser
3. No build steps required - this is a purely front-end implementation

## Customization

### Color Theme

The site uses a dark theme with blue and purple accents. You can customize the colors in the CSS:

- Primary backgrounds: #0f172a, #111827, #1e293b
- Accent colors: #3b82f6 (blue), #8b5cf6 (purple)
- Text colors: #f8fafc (white), #cbd5e1 (light gray)

### Content

- Replace images in the carousel with your own travel destinations
- Update the knowledge base in the chatbot with specific travel information
- Modify the globe to highlight your featured destinations

### Animation Speeds

- Adjust animation durations and easing functions in the GSAP timelines
- Configure Lenis smooth scrolling parameters for different speed effects
