# Darian Terra Homes™ Website

A professional, responsive website for Darian International showcasing Darian Terra Homes™ - The First Architectural Standard for Earth.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Color Scheme**: Matches the original document design
  - Primary Blue: #3465a4
  - Dark Blue: #2f5496
- **Typography**: Uses web-safe fonts (Merriweather serif + Lato sans-serif) that closely match the original design
- **Video Ready**: Includes placeholder section for future video integration
- **SEO Optimized**: Includes meta tags and semantic HTML
- **Print Friendly**: Includes print styles for better document printing

## File Structure

```
website/
├── index.html          # Main HTML file
├── styles.css          # All CSS styling
├── images/             # All images from the original document
│   ├── 1000000000000400000004002E11171B.png
│   ├── 100000000000040000000400474C432B.png
│   ├── 1000000000000400000004005EC94521.png
│   ├── 1000000000000400000006008F59028F.png
│   ├── 100000000000060000000400CB0809A1.png
│   ├── 100000000000060100000360346ED302.png
│   ├── 10000001000001F6000001E8FA796F9B.png
│   └── 10000001000009A1000007B98D6AD3EA.png
└── README.md           # This file
```

## Deploying to GoDaddy

### Method 1: Using GoDaddy File Manager (Recommended)

1. **Log into GoDaddy**:
   - Go to your GoDaddy account and access your hosting control panel
   - Navigate to "File Manager" or "FTP File Manager"

2. **Locate your website directory**:
   - Look for the `public_html` folder (this is typically the root directory for your website)
   - If you have a subdomain, you may have a different folder structure

3. **Upload files**:
   - Upload `index.html` to your root directory (`public_html`)
   - Upload `styles.css` to the same directory
   - Create an `images` folder in your root directory if it doesn't exist
   - Upload all PNG files from the `images` folder to the `images` folder on your server

4. **Verify permissions**:
   - Ensure files have 644 permissions (readable by web server)
   - Ensure folders have 755 permissions

5. **Test your website**:
   - Visit your domain name in a web browser
   - Test on multiple devices to ensure responsive design works

### Method 2: Using FTP Client

1. **Get FTP credentials** from GoDaddy:
   - Host: ftp.yourdomain.com (or provided by GoDaddy)
   - Username: Your FTP username
   - Password: Your FTP password

2. **Connect using an FTP client** (FileZilla, WinSCP, etc.)

3. **Upload files**:
   - Navigate to `public_html` directory
   - Upload `index.html` and `styles.css`
   - Create and upload to `images` folder

4. **Test your website**

## Adding a Video (Future)

When you're ready to add a video:

1. **Option 1 - YouTube/Vimeo Embed**:
   - Upload your video to YouTube or Vimeo
   - Get the embed code
   - In `index.html`, find the video section (around line with `class="video-placeholder"`)
   - Replace the placeholder div with:
     ```html
     <iframe src="YOUR_VIDEO_EMBED_URL" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
     ```

2. **Option 2 - Self-Hosted Video**:
   - Upload video file to your server
   - Replace the video placeholder with:
     ```html
     <video controls width="100%">
         <source src="video/your-video.mp4" type="video/mp4">
         Your browser does not support the video tag.
     </video>
     ```

## Customization Tips

### Changing Colors
- Edit `styles.css`
- Look for color values: `#3465a4`, `#2f5496`, `#2a6099`
- Replace with your preferred colors

### Changing Fonts
- The site uses Google Fonts (Merriweather + Lato)
- To change fonts, modify the `@import` link in `index.html` `<head>` section
- Update font-family references in `styles.css`

### Adding Content
- Edit `index.html` to add or modify sections
- All content sections are clearly marked with comments
- Maintain the semantic HTML structure for best results

## Browser Compatibility

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Support

For any issues or questions:
- Email: info@darianinternational.com
- Company: Darian International LLC

## License

©2026 Darian International LLC - All Rights Reserved
