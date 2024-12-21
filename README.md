# Comprehensive Skill Galaxy Visualization

An interactive 3D visualization tool for exploring and analyzing professional skills and their relationships.

## Features

### Core Visualization
- 3D interactive plot showing skills as nodes in a galaxy
- Skills are organized by proficiency, importance, and depth of expertise
- Dynamic color coding by group or skill size
- Customizable label sizes and animation speeds

### Interactive Controls
- Filter skills by group or search term
- Multiple view presets (Default, Top, Side, Cluster)
- Adjustable animation speed and label size
- Reset functionality to restore default settings

### Skill Details Panel
- Detailed metrics for each skill:
  - Proficiency percentage
  - Importance rating
  - Impact score
  - Number of synergies
- Related skills visualization
- Skill progression indicator

### Relationship Visualization
- Dynamic connection lines between related skills
- Three types of relationships:
  - Related skills (same group)
  - Dependencies (prerequisite skills)
  - Synergies (complementary skills)
- Color-coded connections for different relationship types

## Technical Details

### Dependencies
- Plotly.js for 3D visualization
- Pure JavaScript for interactivity
- HTML5 Canvas for relationship rendering

### Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Responsive design for desktop and mobile devices

### Performance Optimizations
- Efficient data filtering and rendering
- Smooth animations with configurable duration
- Pre-render placeholder for better user experience

## Usage

1. **Basic Navigation**
   - Orbit: Click and drag
   - Zoom: Scroll or pinch
   - Pan: Right-click and drag

2. **Filtering Skills**
   - Use the group dropdown to filter by skill category
   - Type in the search box to find specific skills
   - Reset filters using the reset button

3. **Viewing Skill Details**
   - Click on any skill node to view detailed information
   - View related skills and their connections
   - Monitor skill progression and metrics

4. **Customizing the View**
   - Select different view presets for optimal viewing angles
   - Adjust label sizes for better readability
   - Modify animation speed for smooth transitions

## Implementation Notes

### Data Structure
Skills are represented with the following properties:
