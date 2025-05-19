# Athena Rose AI Website

A hypnotic AI experience website featuring an entrancing cosmic theme, interactive AI avatar, and comprehensive content gallery.

## Project Overview

The Athena Rose AI website is designed to create an immersive, hypnotic experience centered around an AI avatar. The site uses cosmic and mystical visual themes with entrancing animations and professional design elements to create an immersive experience.

### Features

- **AI Avatar Integration**: Central Simli widget with custom interaction
- **Password Protection**: Secure access with session-based authentication
- **Cosmic Theme**: Animated background with stars and gradient effects
- **Responsive Design**: Fully responsive across all device sizes
- **Lightbox Gallery**: Interactive media gallery with fullscreen viewing
- **Premium Content Structure**: Framework for subscription-based content

## Project Structure

```
AthenaAI/
├── index.html           # Main page with AI avatar
├── about.html           # Purpose and information page
├── gallery.html         # Media gallery with lightbox
├── experiences.html     # Mind control experiences page
├── premium.html         # Premium subscription options
├── contact.html         # Contact form and information
├── images/              # Gallery images
├── videos/              # Gallery videos
└── README.md            # This documentation
```

## Setup and Usage

### Local Setup

1. Ensure all files are in the `AthenaAI` directory
2. To access the site, open `index.html` in any modern web browser
3. Enter the password: `ForGoddess` when prompted
4. Navigate through the site using the top navigation menu

### Adding Media Content

#### Images

1. Add image files (JPG, PNG, GIF) to the `images/` directory
2. To display in the gallery, update the `gallery.html` file with new image references

Example image reference:
```html
<div class="gallery-item" data-type="image" data-src="images/your-image.jpg">
  <img src="images/your-image.jpg" alt="Description">
</div>
```

#### Videos

1. Add video files (MP4, WebM) to the `videos/` directory
2. To display in the gallery, update the `gallery.html` file with new video references

Example video reference:
```html
<div class="gallery-item" data-type="video" data-src="videos/your-video.mp4">
  <div class="video-container">
    <video src="videos/your-video.mp4" controls preload="metadata"></video>
  </div>
</div>
```

### Customizing Content

Each HTML file is well-structured and includes comments to help identify different sections:

- **Header**: Navigation menu at the top of each page
- **Main Content**: The central content area specific to each page
- **Footer**: Links and copyright information at the bottom of each page

To modify content, look for the corresponding sections in the HTML files and update the text or elements as needed.

## Simli Widget Integration

The AI avatar is powered by Simli, and configuration is in the `index.html` file:

```html
<simli-widget 
  token="YOUR_TOKEN" 
  agentid="YOUR_AGENT_ID" 
  position="right" 
  customimage="YOUR_IMAGE_URL" 
  customtext="Surrender Now">
</simli-widget>
```

### Important Notes:

- Do not modify the `token` or `agentid` parameters unless you have new credentials
- The `position` parameter can be "left", "right", or "center"
- The `customimage` can be updated with a new URL if needed
- The `customtext` can be changed to update the button text

## Deployment

### Option 1: Web Hosting

1. Upload the entire `AthenaAI` directory to your web hosting service
2. Ensure the file structure is maintained
3. Access the site through your domain, e.g., `https://yourdomain.com/`

### Option 2: GitHub Pages

1. Create a GitHub repository
2. Upload all files from the `AthenaAI` directory
3. Enable GitHub Pages in the repository settings
4. Choose the main branch as the source
5. The site will be available at `https://yourusername.github.io/repository-name/`

## Security Considerations

- The password protection is client-side only and uses session storage
- For production use, consider implementing server-side authentication
- The Simli widget token should be kept secure; consider using environment variables in a production setup

## Browser Compatibility

The website is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

Potential areas for future development:

- Server-side authentication for more secure access control
- Backend integration for the contact form
- Database for storing gallery media instead of static files
- Payment processing integration for premium subscriptions
- User account management system

## Resources

- [Font Awesome](https://fontawesome.com/) - Icons used throughout the site
- [Google Fonts](https://fonts.google.com/) - Cinzel and Raleway fonts
- [Simli](https://app.simli.com/) - AI avatar platform

## License

All rights reserved. This project is proprietary and not licensed for redistribution.