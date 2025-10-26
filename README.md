# Modulo Arithmetic Interactive Learning Experience

An innovative, interactive, and visually engaging educational website that teaches the concept of Modulo Arithmetic in a step-by-step, animated, and AI-narrated way.

## Features

### 🌐 Main Structure

1. **Welcome Page**
   - Animated modular rings and mathematical symbols background
   - Theme switcher (Light / Dark / High-Contrast)
   - Introduction to Addition and Multiplication Modulo

2. **Set Selection Page**
   - Demo Mode: Predefined set {0,1,2,3,4} with modulo 5
   - Custom Mode: User-defined sets with validation
   - Responsive design for all devices

3. **Operation Selection Page**
   - Dropdown for choosing Addition or Multiplication Modulo
   - Input validation for modulo number
   - Visual feedback for errors

4. **Animated Operation Table Page**
   - Step-by-step animation of modular table filling
   - Visual representation of modulo operations
   - Explanation popup after animation completion

5. **Theory Section**
   - Accessible via "Learn Theory" button
   - Detailed explanations of group properties:
     - Closure Property
     - Associativity
     - Identity Element
     - Inverse Property

6. **Property Checking Section**
   - Sequential verification of group properties
   - Visual demonstrations with colored highlights
   - Progress tracker showing property verification status

7. **Narrated Walkthrough Mode**
   - Guided tour highlighting each section
   - AI voice narration explaining each component
   - Skip or replay functionality

8. **Story-Based Explanations**
   - Metaphorical explanations for each group property
   - Lottie.js animations for visual storytelling
   - Simple, engaging narration

9. **Conclusion Screen**
   - Dynamic result message based on property checks
   - Summary of all property verification results
   - Confetti animation for successful group formation
   - Options to restart, try another set, or rewatch animations

## Technologies Used

- **HTML5** - Semantic markup and structure
- **TailwindCSS** - Utility-first CSS framework for styling
- **Vanilla JavaScript** - Core logic and interactivity
- **GSAP** - Smooth animations and transitions
- **Lottie.js** - Lightweight animations for storytelling
- **Web Speech API** - AI voice narration
- **LocalStorage** - Theme preference and user mode persistence

## Design & Aesthetics

- Cool color palette (blue, violet, white) for light mode
- Deep navy and cyan for dark mode
- High-contrast theme for accessibility
- Rounded cards with soft shadows and hover effects
- Fully responsive design for mobile, tablet, and desktop
- Smooth transitions between pages

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd modulo-arithmetic-interactive
   ```

3. Open `index.html` in your browser or serve it using a local server.

## Usage

1. Open the website in a modern browser
2. Select "Start Learning" to begin
3. Choose between Demo Mode or Custom Mode
4. Select your operation (Addition or Multiplication Modulo)
5. Watch the animated table filling process
6. Review the theory section for deeper understanding
7. Check group properties step-by-step
8. View the conclusion to see if your set forms a group

## Project Structure

```
.
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Custom CSS styles
├── js/
│   └── main.js         # Main JavaScript application
└── README.md           # Project documentation
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Credits

Created by Raghav, [Teammate 2 Name], and [Teammate 3 Name]

## License

This project is for educational purposes.