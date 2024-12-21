# Skill Galaxy Visualization

An interactive 3D visualization tool for exploring and analyzing various skills across different domains. The visualization presents skills as a galaxy of interconnected points, allowing users to explore relationships between different skills, their importance, and proficiency levels.

## Features

### 1. Interactive 3D Visualization

- Dynamic 3D scatter plot using Plotly.js
- Skills represented as interactive points in 3D space
- Axes represent:
  - X-axis: Proficiency
  - Y-axis: Importance
  - Z-axis: Depth of Expertise
- Hover functionality showing detailed information for each skill

### 2. Control Panel

The visualization includes a user-friendly control panel with the following features:

#### Group Filtering

- Filter skills by specific groups (e.g., Soft Skills, Data Science, AI, etc.)
- "All Groups" option to view the complete skill set

#### Skill Search

- Real-time search functionality to filter skills by name
- Case-insensitive search for better user experience

#### Color Options

- Two coloring schemes:
  - Color by Group: Different colors for different skill categories
  - Color by Size: Gradient coloring based on skill importance/size

#### Reset Functionality

- "Reset Filters" button to clear all applied filters and return to the default view

### 3. Skill Categories

The visualization includes various skill categories:

- Soft Skills
- Data Science
- Research
- Neuroscience
- Engineering
- Education
- AI
- Programming
- Psychology

### 4. Responsive Design

- Fully responsive layout that adapts to different screen sizes
- Mobile-friendly interface with optimized control panel positioning
- Smooth interactions and transitions

## Technical Details

### Dependencies

- Plotly.js (latest version) for 3D visualization
- Pure HTML/CSS/JavaScript implementation
- No additional frameworks required

### Browser Compatibility

- Works on modern web browsers supporting WebGL
- Recommended browsers: Chrome, Firefox, Safari, Edge

## Usage

1. **Basic Navigation**:
   - Rotate: Click and drag
   - Zoom: Scroll or pinch
   - Pan: Right-click and drag

2. **Filtering**:
   - Use the group dropdown to filter by skill category
   - Type in the search box to find specific skills
   - Switch between color modes using the color options dropdown

3. **Reset**:
   - Click the "Reset Filters" button to clear all applied filters

## Installation

1. Clone the repository
2. Open `index.html` in a modern web browser
3. No build process or server required

## Performance Considerations

- The visualization is optimized for smooth performance with 40+ skills
- Responsive design ensures proper functionality across devices
- Efficient filtering and rendering mechanisms for smooth user experience
