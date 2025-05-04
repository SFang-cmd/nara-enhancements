# CIS 3500: Nara Extension — Enhanced Edition

## Overview
This project is a fork of the original [Nara Chrome Extension](https://github.com/luyiZhang818/Nara-Chrome-Extension), one of the Top 3 winners of the MCIT hackathon. Our goal was to extend Nara’s functionality and provide users with a more supportive and engaging task management experience.

## What’s New in This Fork?

We focused on two major enhancements:

1. **Speech Bubble Encouragement**  
   Whenever a user checks off a task, a new thought bubble asset animates near the appropriate deer, displaying a randomly selected, uplifting message (e.g., “Great job!”, “You’re making progress!”). This provides immediate positive feedback and enriches the interactive experience.

2. **Mood Selection Prompt**  
   Users can now quickly log their mood each day by selecting from a set of expressive emoji icons. The mood selection UI is styled in harmony with the rest of the extension and appears unobtrusively on the main screen.

## Thought Process & Design Choices

- **Consistency in UI/UX:**  
  We used the same visual language and interaction patterns as the original Nara task list to make our new features feel native to the extension.  
  - The mood selector reuses the card and icon layouts from the task list, ensuring style consistency.
  - The speech bubble employs a newly designed SVG/PNG asset that matches the playful aesthetic of the deers and background art.

- **User Delight:**  
  The encouraging speech bubbles appear in context, right where the user is interacting, for immediate visual feedback and motivation.

- **Modularity & Maintainability:**  
  Feature logic for encouragement and mood selection is encapsulated in their own modules, allowing for easy future updates or further customization.

- **Accessibility:**  
  Emphasis on high-contrast messages and keyboard navigation for the mood selector, so all users can benefit from the features.

## Getting Started

1. **Clone This Fork:**
   ```sh
   git clone https://github.com/<your-username>/nara-extension-starter.git
   ```

2. **Install & Load Extension:**
   - Open Chrome and go to `chrome://extensions/`
   - Enable "Developer mode" in the top right
   - Click "Load unpacked" and select the cloned repo folder

3. **Development Workflow:**
   - Edit code in your preferred text editor (VS Code recommended)
   - Use standard Git workflow for commits and pull requests

---

Happy coding, and enjoy your more encouraging Nara! 🦌✨
