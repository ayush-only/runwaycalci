# Founder’s Runway Calculator

A clean and intuitive web application that helps founders visualize their financial runway and understand how long they can sustain operations based on their current cash flow.

## The Idea

Many startups fail not because of bad ideas, but because they run out of money.

This tool provides a simple way to:
- Track financial health
- Understand burn rate impact
- Make better decisions before reaching “zero day”

## Features

### Core Functionality
- Input: Total Cash, Monthly Burn, Monthly Revenue
- Automatic runway calculation (months + days)
- Net burn calculation (Burn − Revenue)

###  Visual Feedback
- 🟢 **Safe Zone** (≥ 6 months)
- 🟡 **Warning Zone** (< 6 months)
- 🔴 **Urgent Zone** (< 3 months)
- Dynamic UI color changes based on runway

###  Multi-Currency Support
- Supports INR, USD, EUR
- Inputs can be in different currencies
- Automatic conversion before calculation

###  User Experience
- Dark / Light mode toggle
- Hover animations for better interaction
- Clean and responsive design (mobile-friendly)


##  Tech Stack

- HTML  
- CSS  
- JavaScript  


##  Design Approach

The focus was on:
- **Clarity over complexity** → minimal inputs, instant output  
- **Visual communication** → color-based urgency states  
- **User experience** → smooth interactions and feedback  

The goal was to make financial insights understandable at a glance.


##  Key Decisions

- Used simple frontend-only architecture for speed and accessibility  
- Added multi-currency support to simulate real-world usage  
- Designed UI states (Safe/Warning/Urgent) to guide user decisions  


##  Future Improvements

- More Currency options
- API-based real-time currency conversion  
- Data persistence (save user inputs)  
- Interactive charts for cash flow visualization  
- Export/share results  


##  How to Run

1. Download or clone the repository  
2. Open `index.html` in your browser  


##  What I Learned

- Building UI with user-focused thinking  
- Translating simple logic into meaningful visual feedback  
- Improving usability through small details  

##  Project Goal

This project was built as part of an E-Cell selection task to demonstrate:
- Attention to detail  
- Technical implementation  
- Product thinking 
