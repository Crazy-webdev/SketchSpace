# SketchSpace

**SketchSpace** is a cutting-edge collaborative whiteboarding application designed for real-time team collaboration, creativity, and productivity. With **SketchSpace**, you can create, draw, and interact with a shared whiteboard seamlessly. Whether you're brainstorming ideas, working on projects, or just sketching for fun, SketchSpace is your perfect canvas. Plus, it comes with integrated **Stripe** payment gateway, allowing users to easily manage their payments and subscriptions.

## Features

- **Real-time Collaboration**: 
  - Work with multiple users on the same whiteboard simultaneously. Sketch, draw shapes, and share ideas with your team in real time.
  
- **Record and Playback**: 
  - Capture your whiteboard actions and replay them later. Whether it’s brainstorming or presenting an idea, you can always replay your session and remember every step.
  
- **User Authentication**: 
  - Secure login and registration system powered by JWT authentication. Manage your workspace and access personal data securely.
  
- **Payment Integration (Stripe)**: 
  - Integrated **Stripe** payment gateway for easy transactions. Whether you're buying credits, upgrading to premium features, or subscribing, payments are seamless and secure.

- **Interactive Whiteboard**: 
  - Use a variety of drawing tools such as shapes, lines, and freehand drawing. With real-time updates, everyone can see and contribute to the whiteboard simultaneously.

- **Customizable Canvas**: 
  - Adjust the whiteboard size, colors, and tools to fit your specific needs. No limits on creativity or productivity.

## Tech Stack

### Frontend
- **React** (v18+) for building the user interface
- **Recoil** for state management
- **Fabric.js** for rendering the drawing canvas
- **Vite** as the build tool for fast development and optimized production builds
- **Tailwind CSS** for modern, responsive styling
- **Stripe** for payment integration

### Backend
- **Node.js** with **Express** to handle API requests
- **MongoDB** with **Mongoose** for database management
- **Socket.io** for real-time communication between clients and server
- **JWT Authentication** for secure user sessions
- **Stripe** for payment gateway integration
- **Winston** for logging
- **Zod** for input validation