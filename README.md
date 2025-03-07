# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

- 🔥 Core Features

- To use it you will have to create a OPENAI Keys and set inot .env file. Create a .env file in root of project.
- 
1️⃣ Chat System


-> Real-time Conversation – Users can enter text prompts and receive AI-generated responses.

-> Persistent Chat History – Conversations are stored and categorized under unique chat titles.

-> Scrollable Chat Window – Ensures the latest messages are always visible.


2️⃣ Chat Management

-> New Chat Creation – Users can start a fresh conversation anytime.

-> Chat History Sidebar – Displays previous and ongoing conversations.

-> Local Storage Integration – Saves chat history locally for persistent sessions.

3️⃣ API Integration


-> OpenAI GPT-4 API – Uses OpenAI’s API for AI-generated responses.

-> Secure API Calls – Sends POST requests with headers and authentication.

-> Error Handling – Displays messages for API rate limits and connectivity issues.


4️⃣ User Experience (UX)


-> Loading Indicator – Displays “Processing…” while awaiting responses.

-> Sidebar Toggle – Collapsible sidebar for better accessibility.

-> Responsive Design – Works on both desktop and mobile screens.

-> User & AI Profile Icons – Enhances message clarity with user avatars.


⚙️ Technical Features

1️⃣ React Features

-> Functional Components – Uses modular and reusable components.

-> React Hooks – Manages state and effects (useState, useEffect, useRef, etc.).

-> Event Handling – Manages input, form submission, and sidebar interactions.


2️⃣ State Management

-> Local State (useState) – Tracks user input, messages, chat history, and loading states.

-> Context API (Upcoming Refactor) – Will manage state globally for better performance.


3️⃣ Performance Optimizations

-> Debounced Scroll – Uses setTimeout for smooth auto-scrolling.

-> useCallback & useLayoutEffect – Optimizes sidebar and UI interactions.

![Screenshot (52)](https://github.com/user-attachments/assets/c80a2d70-cadd-4a11-b7d2-539310314cc8)
