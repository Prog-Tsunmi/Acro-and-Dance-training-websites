# Acro and Dance training websites

## Overview

Two advanced training web applications designed for boys' physical development:

1. **Advanced Yoga Training for Boys** - A comprehensive yoga training system with guided workouts, form analysis, and progress tracking.
2. **Advanced Circus Training for Boys** - A zero-bug certified circus training application focusing on aerial skills, apparatus work, and safety-focused routines.

## Features

### Common Features
- **Multi-step Training Flow**: Structured 5-step process from selection to feedback
- **Adaptive Workouts**: 5-minute and 10-minute workout options
- **Media Integration**: Camera recording, automatic photos, or no-photo options
- **Progress Tracking**: Real-time timers and progress bars
- **Safety Checklists**: Equipment and ability verification before training
- **Responsive Design**: Works on desktop and mobile devices
- **Feedback System**: Post-workout ratings and comments

### Yoga Training Specific
- **Subtitled Instructions**: Step-by-step guidance for each pose
- **Flexibility Focus**: Exercises designed for splits and back flexibility
- **Form Analysis**: Video recording for technique improvement
- **Ballet Integration**: Specific attire requirements for optimal performance

### Circus Training Specific
- **Zero-Bug Certified**: Robust error handling and state management
- **Apparatus Training**: Hammock, pole, hoop, and floor exercises
- **Safety First Design**: Comprehensive equipment and ability checklists
- **Advanced State Management**: Singleton pattern with proper cleanup
- **Dress Code Options**: Multiple attire configurations for different apparatus

## Technical Specifications

### Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile Safari and Chrome for mobile devices
- Requires camera access for media features (optional)

### Technologies Used
- **HTML5**: Semantic markup and structure
- **CSS3**: Custom properties, flexbox, grid, responsive design
- **JavaScript**: ES6+ with modular architecture
- **Media APIs**: getUserMedia, MediaRecorder, Canvas API
- **Font Awesome**: Icon library for visual elements

### Performance Features
- Debounced event handlers
- RequestAnimationFrame for smooth animations
- Proper cleanup of media streams and timers
- Lazy loading of images
- Reduced motion support

## Installation & Usage

### Quick Start
1. Download the HTML files
2. Open in any modern web browser
3. No server or dependencies required

### Steps to Use
1. **Select Workout Duration**: Choose 5 or 10 minute session
2. **Complete Checklists**: Verify equipment and ability requirements
3. **Choose Media Option**: Select camera, photos, or no media
4. **Follow Training**: Real-time instructions and timers
5. **Provide Feedback**: Rate and comment on your session

## Browser Permissions

### Required Permissions
- **Camera Access**: For video recording and photo capture
- **Microphone**: Not required (audio disabled)
- **Storage**: For saving media files (optional)

### Permission Notes
- Permissions are requested only when needed
- Users can choose "No Photography" to avoid camera prompts
- All media stays local unless explicitly saved

## Safety Guidelines

### Essential Safety Rules
1. **Always use proper equipment** as specified in checklists
2. **Clear sufficient space** around training areas
3. **Verify apparatus security** before use
4. **Stop immediately** if experiencing pain or discomfort
5. **Have a spotter available** for advanced maneuvers

### Equipment Requirements
- Yoga mat (for yoga training)
- Secured aerial apparatus (for circus training)
- Proper attire as specified in checklists
- Safety mats and clearance space

## Development & Customization

### File Structure
```
yoga-training.html      # Main yoga application
circus-training.html    # Main circus application
```

### Customization Points
1. **Exercise Data**: Modify `exercises5Min` and `exercises10Min` arrays
2. **Checklist Items**: Update checklist requirements in HTML
3. **Styling**: Modify CSS variables in `:root` selectors
4. **Timing**: Adjust duration constants in configuration objects

### Debug Mode
The circus training app includes debug mode when accessed via `localhost`:
- Exposes application objects to console
- Enhanced error reporting
- Development tools accessible

## Support & Contact

### Technical Support
- **Contact**: dengluffy1@gmail.com
- **Issue Reporting**: Please include browser version and console logs

### Feature Requests
Submit requests via email with:
1. Clear description of desired feature
2. Use case scenario
3. Expected behavior

## License Information

### Important Notice
These files are licensed under **tsunmi's custom license**. 

### License Verification
Users **MUST** go to the **home page repositories** to check the universal license terms and conditions. The specific licensing details, restrictions, and permissions are defined in the main repository's license documentation.

### Key Points
- ❗ **Do not assume standard open-source licenses apply**
- ❗ **Commercial use may require additional permissions**
- ❗ **Distribution rights are specified in the custom license**
- ✅ Always refer to the main repository for authoritative license information

## Version History

### Current Version
- **Yoga Training**: Production version with subtitle system
- **Circus Training**: v3.0.0-zero-bug with enhanced stability

### Recent Updates
- Fixed mobile viewport issues
- Improved camera permission handling
- Enhanced error recovery systems
- Added print and reduced motion support

## Acknowledgments

### Inspiration
- Professional yoga and circus training methodologies
- Safety-first approach to physical training
- Progressive overload principles

### Technical Thanks
- Font Awesome for icon library
- Modern browser API developers
- Open web standards community

---

**Remember**: Always consult with a professional trainer before attempting new physical exercises, and never train beyond your current ability level. Safety should always be the top priority.
