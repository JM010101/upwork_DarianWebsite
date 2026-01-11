# Style Guide & Design Recommendations

## Current Design Implementation

The website has been created to match your LibreOffice document as closely as possible, with the following design choices:

### Color Scheme

**Current Colors (From Your Document)**:
- **Primary Blue**: `#3465a4` - Used for headings, bold text, and accents
- **Dark Blue**: `#2f5496` - Used for brand elements and secondary text
- **Light Blue**: `#2a6099` - Used for some descriptive text
- **Black**: `#000000` - Used for body text
- **White**: `#ffffff` - Background color

### Typography

**Current Font Stack**:
- **Headings**: Merriweather (serif) → Liberation Serif → Times New Roman
- **Body Text**: Lato (sans-serif) → Arial → Liberation Sans

These fonts were chosen to closely match the original document's font choices (Liberation Serif and Arial).

## Design Recommendations

### Font Suggestions

If you'd like to consider alternative fonts, here are some recommendations that would work well for a professional, trustworthy company website:

1. **More Modern Serif Options**:
   - **Playfair Display** - Elegant, modern serif for headings
   - **Crimson Text** - Classic, readable serif
   - **PT Serif** - Professional serif with good readability

2. **Clean Sans-Serif Options**:
   - **Open Sans** - Very readable, professional
   - **Roboto** - Modern, clean, widely used
   - **Inter** - Contemporary, excellent for web

3. **Professional Combination**:
   - Headings: **Montserrat** (bold, modern)
   - Body: **Source Sans Pro** (clean, readable)

**To change fonts**, edit the Google Fonts link in `index.html` (around line 12) and update the `font-family` properties in `styles.css`.

### Color Suggestions

Your current blue color scheme (`#3465a4`) is excellent for conveying trust, stability, and professionalism. Here are some complementary color suggestions:

1. **Accent Colors** (for CTAs or highlights):
   - **Earth Tones**: `#8B7355` (tan/brown) - connects to "terra" theme
   - **Green**: `#4A7C59` (muted green) - emphasizes sustainability
   - **Orange**: `#C45911` - warm, inviting (already used sparingly in your doc)

2. **If You Want to Enhance**:
   - Add a subtle gradient background: Light blue to white
   - Use lighter blue (`#E8F1F8`) for section backgrounds
   - Consider a subtle gray (`#F5F5F5`) for footer

3. **Contrast Improvements**:
   - Your current contrast is good for accessibility
   - Consider slightly lighter blue for better readability on mobile

### Layout Recommendations

1. **Current Layout**: Follows document structure closely - ✅ Good for familiarity

2. **Potential Enhancements**:
   - Add subtle shadows to images for depth
   - Consider adding hover effects to links/images
   - Add smooth scroll animations (optional)

3. **Mobile Optimization**: Already implemented - responsive design works on all devices

## Making Changes

### To Change Colors:

1. Open `styles.css`
2. Use Find & Replace:
   - Find: `#3465a4` → Replace with your new color
   - Find: `#2f5496` → Replace with your new color

### To Change Fonts:

1. Open `index.html`
2. Update the Google Fonts link (line ~12):
   ```html
   <link href="https://fonts.googleapis.com/css2?family=YOUR_FONT:wght@400;700&display=swap" rel="stylesheet">
   ```
3. Open `styles.css`
4. Update font-family properties:
   ```css
   font-family: 'YOUR_FONT', fallback, serif;
   ```

## Design Philosophy

The current design follows these principles:

1. **Trustworthy**: Blue color scheme conveys reliability
2. **Professional**: Serif fonts for headings add gravitas
3. **Readable**: Sans-serif body text ensures easy reading
4. **Clean**: Minimal design focuses on content
5. **Accessible**: Good color contrast and readable fonts

## Final Recommendations

**For a company showcasing innovative housing technology**, I recommend:

1. **Keep the current blue** - It works well and matches your document
2. **Consider adding**: Subtle earth tones as accents (tan/brown) to emphasize "terra"
3. **Fonts are good as-is** - Professional and readable
4. **Add subtle animations** - Small fade-ins on scroll (optional, doesn't affect budget)

The website is ready to deploy as-is and will look professional and trustworthy!
