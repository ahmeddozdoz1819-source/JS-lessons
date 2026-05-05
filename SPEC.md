# JavaScript Learning Website - Specification

## Project Overview
- **Project Name**: JS Mastery Hub
- **Type**: Educational single-page website
- **Core Functionality**: Interactive JavaScript lessons with code examples and live practice
- **Target Users**: Beginner to intermediate JavaScript learners

## UI/UX Specification

### Layout Structure
- **Header**: Fixed navigation with logo and lesson category links
- **Hero Section**: Welcoming intro with quick stats
- **Sidebar**: Collapsible lesson navigation (left)
- **Main Content**: Lesson cards with interactive code blocks
- **Footer**: Credits and resources

### Responsive Breakpoints
- Desktop: 1200px+ (full sidebar)
- Tablet: 768px-1199px (collapsible sidebar)
- Mobile: <768px (hamburger menu, stacked layout)

### Visual Design - 2 Color Principle

**Color Palette (Maximum 3 colors)**
- Primary: `#1a1a2e` (Deep navy - backgrounds)
- Secondary: `#e94560` (Coral red - accents, buttons, highlights)
- Tertiary: `#0f3460` (Dark blue - cards, sections)
- Text Primary: `#ffffff`
- Text Secondary: `#a0a0a0`
- Code Background: `#16213e`

### Typography
- **Headings**: 'Outfit', sans-serif (700 weight)
- **Body**: 'Source Sans Pro', sans-serif (400/600 weight)
- **Code**: 'JetBrains Mono', monospace

### Visual Effects
- Smooth hover transitions (0.3s ease)
- Card hover lift effect with subtle shadow
- Code block syntax highlighting
- Staggered reveal animations on load
- Interactive code playground with run button

### Components

1. **Navigation Bar**
   - Logo with JS icon
   - Category pills
   - Active state indicator

2. **Lesson Card**
   - Title with icon
   - Description
   - Expandable code example
   - "Try It" interactive button
   - Copy code button

3. **Code Playground**
   - Textarea for code input
   - Run button
   - Output display area
   - Clear button

4. **Progress Indicator**
   - Completed lessons counter
   - Visual progress bar

5. **Category Tabs**
   - Basics, Functions, DOM, Arrays, Async, ES6+

## Functionality Specification

### Core Features
1. **Lesson Categories** (organized, ordered):
   - JS Basics (variables, data types, operators)
   - Control Flow (if/else, loops, switch)
   - Functions (declarations, expressions, arrow, scope)
   - Arrays (methods, iteration)
   - Objects & Classes
   - DOM Manipulation
   - Async JavaScript (promises, async/await)
   - ES6+ Features

2. **Interactive Code Runner**
   - Write code in textarea
   - Execute with eval() (sandboxed)
   - Display output in console area
   - Error handling with friendly messages

3. **Code Examples**
   - Syntax-highlighted code blocks
   - Copy to clipboard functionality
   - Expand/collapse examples

4. **Lesson Progress**
   - Track completed lessons (localStorage)
   - Progress bar visualization

5. **Navigation**
   - Smooth scroll to sections
   - Active section highlighting
   - Mobile hamburger menu

### User Interactions
- Click category → scroll to section
- Click lesson → expand/collapse
- Click "Try It" → open code playground
- Click "Run" → execute code, show output
- Click "Copy" → copy code to clipboard

### Data Handling
- Progress saved in localStorage
- No backend required

## Acceptance Criteria
1. All 8 lesson categories display correctly
2. Code playground executes JS and shows output
3. Copy button copies code to clipboard
4. Progress persists across page reloads
5. Responsive on all breakpoints
6. Animations play smoothly
7. Only 2-3 colors used throughout
8. All code examples are accurate and working