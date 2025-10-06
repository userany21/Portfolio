# Portfolio


# Project 1: Ecommerce Website

This is an ecommerce website built from scratch.

### Backend:
This is a server app built with Python and the Django framework. It handles rendering pages, business logic, and interacting with the databases.  
  
**Language:** Python  
**Framework:** Django    
**Database:** SQLite for core application data.  
**External Services:** Supabase is used for additional data management.  
**Email:** SMTP for sending emails, such as magic links for authentication or order confirmations.  
**N8N:** Sends newsletter emails weekly.  

### Frontend:
The frontend was designed in Figma and translated into custom HTML/CSS, then integrated with Django templates for server-side rendering. The implementation includes custom JavaScript for dynamic features like the shopping cart.  
  
**Design:** Figma (UI prototype)  
**Templating:** Django Template Language (DTL)  
**Styling:** Bootstrap 5 and custom stylesheets.  
**JavaScript:** Vanilla JavaScript along with the Supabase JS client for direct interaction with Supabase from the browser.  

### Shared:
**Package Management:** pip 

------------------------------------------------------------------------------------------------------------

# Project 2: Smart Mirror

This is a smart mirrror with 3 main components: a backend server, mobile app, and dashboard display.

### Backend:
Node.js server built with Express. Managed widget data, API requests, and real time updates with the dashboard via Websockets.  
  
**Runtime:** Node.js  
**Framework:** Express.js  
**Real-time Communication:** ws (WebSockets)  
**Database/External Services:** Interacts with Supabase for data.  

### Mobile App:
An IOS & Android mobile application built with React Native (Expo) where users are able to customize their widgets, manage positions and connect to smart mirrors through local networks.  
  
**Framework:** React Native (managed with Expo)  
**Navigation:** React Navigation  
**State Management:** Zustand  
**UI:** Core React Native components  

### Dashboard (Frontend):
A display bult with React and Vite. This display shows all the widgets that the user picks from the mobile app. Only features available so far are the weather forecast, clock, and system stats. 
  
**Framework:** React  
**Build Tool:** Vite  
**Routing:** React Router  
**State Management:** Zustand  

### Shared:
**Language:** TypeScript for type safety across all packages.  
**Package Management:** npm  

-----------------------------------------------------------------------------------------------------------

# Project 3: N8N Tiktok Automation

Developed an end-to-end automation workflow in n8n to generate and render TikTok videos with a single click. This pipeline integrates OpenAI for dynamic script creation, Text-to-Speech for voiceovers, a Google Drive video database for background footage, and the Creatomate API for final video rendering.  

### Key Achievement: 
Reduced video production time by over 80%.  

### Impact: 
The workflow is used to produce content for two TikTok accounts with a combined following of over 130,000.  

### Tech Stack: 
n8n, OpenAI API, Creatomate API, Google Drive API, REST APIs.  

------------------------------------------------------------------------------------------------------------

