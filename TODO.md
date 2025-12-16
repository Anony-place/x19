# TODO: Improve UI and Fix Voice Issues

## Completed Tasks
- [x] Add media query for large desktops (min-width: 1200px) - full width, no centering, no space
- [x] Fine-tune small mobile (<=480px) - reduce button sizes to 40px, adjust padding/gaps
- [x] Test responsiveness across different screen sizes
- [x] Make any necessary adjustments for better compatibility
- [x] Switch to a professional dark theme: Dark background (#1a1a1a), light text (#ffffff), accent colors (blues and grays)
- [x] Improve typography: Use a more professional font stack, adjust font sizes for better readability
- [x] Enhance message bubbles: More subtle shadows, better contrast, professional styling
- [x] Refine header and input area: Cleaner design, better spacing
- [x] Add subtle professional animations: Smooth transitions, hover effects
- [x] Ensure overall polish: Remove flashy elements, focus on clean, minimal design

## New Tasks for UI Improvements
- [ ] Update color scheme to modern dark theme with vibrant accents (e.g., dark background, neon highlights)
- [ ] Add more animations (e.g., message slide-ins, button hover effects, enhanced typing indicators)
- [ ] Enhance gradients, shadows, and visual elements for engaging look
- [ ] Improve responsiveness and add subtle patterns or effects

## New Tasks for Voice Fixes
- [ ] Add better error handling and user feedback for TTS failures
- [ ] Improve speech recognition reliability (handle permissions, add retries)
- [ ] Ensure fallbacks work smoothly and log issues for debugging

## New Tasks for Bot Prompt and UI Enhancements
- [x] Update system prompt in index.html to tone down vulgarity and make responses clearer and more natural
- [x] Enhance style.css for better message bubbles (add tails, improved shadows), smoother animations (fade-ins, enhanced typing indicator), and overall chat app feel
- [x] Update TODO.md with new tasks for these improvements and testing

## New Tasks for File Uploader Feature
- [x] Add file input button next to send button for uploading images, PDFs, etc.
- [x] Handle file selection and display in messages (images as previews, PDFs as links)
- [x] Update sendMessage function to include files in chat history
- [x] Add event listeners for file button and input

## New Tasks for Database Migration, Microservices Architecture, and AI Art Generation
- [ ] Set up Node.js/Express backend in 'backend' folder with microservices structure
- [ ] Configure PostgreSQL database with migration scripts for chats, users, files
- [ ] Create Chat microservice (integrate Groq API)
- [ ] Create User microservice (handle user management)
- [ ] Create AI Art microservice (integrate OpenAI DALL-E API)
- [ ] Update frontend (index.html) to call backend APIs via fetch, remove direct Groq calls
- [ ] Add UI elements for art generation (prompt input, image display) in index.html and style.css
- [ ] Secure API keys with environment variables (.env file)
- [ ] Test backend APIs, database persistence, and integrations
- [ ] Update frontend for art generation UI and backend integration

## Followup Steps
- [ ] Test UI on desktop and mobile for responsiveness
- [ ] Test voice features (TTS and speech recognition) in different browsers
- [ ] Verify API keys and permissions
- [ ] Test bot responses for naturalness and clarity
- [ ] Update TODO.md with completion status

## Current Implementation Steps
- [x] Update color scheme to neon accents (cyan, magenta)
- [x] Add slide-in animations for messages
- [x] Enhance gradients and shadows
- [x] Add subtle background pattern to messages area
- [x] Improve button hover effects and typing indicator
