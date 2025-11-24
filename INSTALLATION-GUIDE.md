# Zierhofer WordPress Theme - Installation Guide

**Version:** 3.0.0  
**Developer:** Black10998  
**Repository:** [https://github.com/Black10998/zierhofer-alkhala](https://github.com/Black10998/zierhofer-alkhala)

---

## Quick Start

1. Download `zierhofer-wordpress-theme-v3.0.zip` from the repository
2. Go to WordPress Admin → Appearance → Themes → Add New → Upload Theme
3. Choose the ZIP file and click "Install Now"
4. Click "Activate" after installation
5. Configure settings in Appearance → Customize

---

## Detailed Installation Instructions

### Prerequisites

Before installing the theme, ensure your WordPress installation meets these requirements:

- **WordPress Version:** 5.0 or higher
- **PHP Version:** 7.4 or higher
- **MySQL Version:** 5.6 or higher
- **Server:** Apache or Nginx
- **Memory Limit:** 128MB minimum (256MB recommended)

### Step 1: Download the Theme

1. Go to [https://github.com/Black10998/zierhofer-alkhala](https://github.com/Black10998/zierhofer-alkhala)
2. Download `zierhofer-wordpress-theme-v3.0.zip`
3. Save the file to your computer
4. **Do not extract the ZIP file** - WordPress needs it zipped

### Step 2: Upload and Install

#### Method A: WordPress Admin (Recommended)

1. Log in to your WordPress admin panel
2. Navigate to **Appearance → Themes**
3. Click **Add New** at the top
4. Click **Upload Theme** button
5. Click **Choose File** and select `zierhofer-wordpress-theme-v3.0.zip`
6. Click **Install Now**
7. Wait for the upload and installation to complete
8. Click **Activate** to enable the theme

#### Method B: FTP Upload

1. Extract `zierhofer-wordpress-theme-v3.0.zip` on your computer
2. Connect to your server via FTP
3. Navigate to `/wp-content/themes/`
4. Upload the `zierhofer-wordpress-theme` folder
5. Go to WordPress Admin → Appearance → Themes
6. Find "Zierhofer Installateur" and click **Activate**

### Step 3: Initial Configuration

After activation, configure the theme:

1. Go to **Appearance → Customize**
2. Configure the following sections:

#### Site Identity
- Upload your logo (recommended size: 300x100px)
- Set site title and tagline

#### Company Information
- Company Name: `Sana Tec`
- Company Tagline: `Innungs- und Meisterfachbetrieb in Berlin`
- Phone Number: Your phone number
- Emergency Phone: Your 24h emergency number
- Email Address: Your email
- Physical Address: Your complete address
- Opening Hours: Your business hours

#### Hero Section
- Hero Title: Main headline for homepage
- Hero Subtitle: Secondary headline
- Hero Description: Brief company description

#### About Section
- About Title: Section heading
- About Content: Company description text

#### Footer Settings
- Footer Copyright: Copyright text
- Developer Credit: `Developed by Black10998` (pre-filled)

3. Click **Publish** to save changes

### Step 4: Create Pages

Create the following pages with their respective templates:

#### Homepage (Front Page)
1. Go to **Pages → Add New**
2. Title: `Home` or `Startseite`
3. Leave content empty (template handles everything)
4. Publish the page
5. Go to **Settings → Reading**
6. Set "Your homepage displays" to "A static page"
7. Select your Home page as "Homepage"

#### Contact Page (Kontakt)
1. Go to **Pages → Add New**
2. Title: `Kontakt`
3. Page Attributes → Template: Select **Kontakt**
4. Add any additional content if needed
5. Publish the page

#### Career Page (Karriere)
1. Go to **Pages → Add New**
2. Title: `Karriere`
3. Page Attributes → Template: Select **Karriere**
4. Add any additional content if needed
5. Publish the page

#### Emergency Service Page (Notdienst)
1. Go to **Pages → Add New**
2. Title: `Notdienst`
3. Page Attributes → Template: Select **Notdienst**
4. Add any additional content if needed
5. Publish the page

#### Legal Pages
1. Create **Impressum** page (standard page template)
2. Create **Datenschutz** page (standard page template)
3. Add your legal content to these pages

### Step 5: Setup Navigation Menu

1. Go to **Appearance → Menus**
2. Click **Create a new menu**
3. Name it "Primary Menu" or "Hauptmenü"
4. Add pages to the menu:
   - Home / Startseite
   - Kontakt
   - Karriere
   - Notdienst
5. Arrange pages in desired order
6. Under "Menu Settings", check **Primary Menu**
7. Click **Save Menu**

### Step 6: Configure Widgets (Optional)

1. Go to **Appearance → Widgets**
2. Add widgets to footer areas:
   - **Footer Widget Area 1**: Company info widget
   - **Footer Widget Area 2**: Contact info widget
   - **Footer Widget Area 3**: Opening hours widget
3. Customize widget content as needed

### Step 7: Install Recommended Plugins (Optional)

For enhanced functionality, install these plugins:

#### Contact Form 7
- For contact forms on the Kontakt page
- Install from **Plugins → Add New**
- Search for "Contact Form 7"
- Install and activate

#### Yoast SEO
- For search engine optimization
- Install from **Plugins → Add New**
- Search for "Yoast SEO"
- Install and activate

#### WP Super Cache
- For performance optimization
- Install from **Plugins → Add New**
- Search for "WP Super Cache"
- Install and activate

---

## Post-Installation Checklist

After installation, verify the following:

### Visual Check
- [ ] Homepage displays correctly
- [ ] All sections are visible
- [ ] Images load properly
- [ ] Fonts display correctly
- [ ] Colors match the design
- [ ] Layout is correct

### Functionality Check
- [ ] Navigation menu works
- [ ] Mobile menu toggles correctly
- [ ] All internal links work
- [ ] Smooth scrolling works for anchor links
- [ ] Back to top button appears on scroll
- [ ] Contact form submits (if Contact Form 7 installed)

### Content Check
- [ ] Company information displays correctly
- [ ] Phone numbers are correct
- [ ] Email address is correct
- [ ] Address is correct
- [ ] Opening hours are correct
- [ ] Developer credit is visible in footer

### Responsive Check
- [ ] Desktop view (1920px)
- [ ] Laptop view (1366px)
- [ ] Tablet landscape (1024px)
- [ ] Tablet portrait (768px)
- [ ] Mobile view (375px)

### Browser Check
- [ ] Chrome
- [ ] Firefox
- [ ] Safari
- [ ] Edge

---

## Customization Guide

### Changing Content

#### Via WordPress Customizer
1. Go to **Appearance → Customize**
2. Navigate to the section you want to edit
3. Make your changes
4. Click **Publish**

#### Via Page Editor
1. Go to **Pages → All Pages**
2. Click on the page you want to edit
3. Edit content in the editor
4. Click **Update**

### Changing Images

#### Logo
1. Go to **Appearance → Customize → Site Identity**
2. Click **Select Logo**
3. Upload or select your logo
4. Adjust cropping if needed
5. Click **Publish**

#### Service Images
1. Go to **Media → Library**
2. Find the image you want to replace
3. Click **Edit**
4. Upload new image
5. Update

### Changing Colors (Advanced)

To change colors, you'll need to edit the theme's CSS:

1. Go to **Appearance → Customize → Additional CSS**
2. Add custom CSS rules
3. Example:
```css
/* Change primary color */
.btn, .builder_button {
    border-color: #YOUR_COLOR;
}

/* Change link color */
a {
    color: #YOUR_COLOR;
}
```

### Adding Custom Code

To add custom code without modifying theme files:

1. Install "Code Snippets" plugin
2. Add your custom PHP, CSS, or JavaScript
3. This preserves changes during theme updates

---

## Troubleshooting

### Theme Won't Install

**Problem:** Upload fails or error message appears

**Solutions:**
- Check file size limit in WordPress (increase if needed)
- Verify ZIP file is not corrupted
- Try FTP upload method instead
- Check server permissions

### Images Not Loading

**Problem:** Images appear broken or don't load

**Solutions:**
- Regenerate thumbnails (use plugin)
- Check file permissions on uploads folder
- Verify image paths are correct
- Clear browser cache

### Menu Not Appearing

**Problem:** Navigation menu doesn't show

**Solutions:**
- Verify menu is assigned to "Primary Menu" location
- Check if menu has items added
- Clear cache if using caching plugin
- Check theme is activated

### Customizer Changes Not Saving

**Problem:** Changes in Customizer don't save

**Solutions:**
- Check browser console for JavaScript errors
- Disable conflicting plugins temporarily
- Increase PHP memory limit
- Clear browser cache

### Mobile Menu Not Working

**Problem:** Mobile menu doesn't toggle

**Solutions:**
- Clear browser cache
- Check JavaScript console for errors
- Verify jQuery is loaded
- Disable conflicting plugins

### Contact Form Not Working

**Problem:** Contact form doesn't submit

**Solutions:**
- Install Contact Form 7 plugin
- Create a contact form
- Add shortcode to Kontakt page
- Configure email settings

---

## Maintenance

### Regular Updates

1. **Backup First:** Always backup before updates
2. **Check Compatibility:** Verify WordPress version compatibility
3. **Test on Staging:** Test updates on staging site first
4. **Update Theme:** Download new version and install

### Backup Recommendations

Use a backup plugin:
- **UpdraftPlus** (recommended)
- **BackWPup**
- **Duplicator**

Schedule automatic backups:
- Daily database backups
- Weekly file backups
- Store backups off-site

### Performance Optimization

1. **Install Caching Plugin:**
   - WP Super Cache
   - W3 Total Cache
   - WP Rocket (premium)

2. **Optimize Images:**
   - Use Smush or ShortPixel
   - Compress images before upload
   - Use WebP format when possible

3. **Enable CDN:**
   - Cloudflare (free)
   - StackPath
   - KeyCDN

4. **Minify Assets:**
   - Use Autoptimize plugin
   - Combine CSS/JS files
   - Remove unused code

---

## Support

### Getting Help

1. **Check Documentation:**
   - README.md in theme folder
   - VALIDATION-CHECKLIST.md
   - This installation guide

2. **Common Issues:**
   - Review troubleshooting section above
   - Check WordPress.org forums
   - Search for similar issues online

3. **Contact Developer:**
   - Repository: [https://github.com/Black10998/zierhofer-alkhala](https://github.com/Black10998/zierhofer-alkhala)
   - Create an issue on GitHub
   - Provide detailed description and screenshots

### Reporting Bugs

When reporting bugs, include:
- WordPress version
- PHP version
- Theme version
- Active plugins list
- Error messages (if any)
- Screenshots of the issue
- Steps to reproduce

---

## Uninstallation

To remove the theme:

1. **Activate Another Theme First:**
   - Go to **Appearance → Themes**
   - Activate a different theme (e.g., Twenty Twenty-Four)

2. **Delete Theme:**
   - Find "Zierhofer Installateur" theme
   - Click **Theme Details**
   - Click **Delete** in bottom right
   - Confirm deletion

3. **Clean Up (Optional):**
   - Remove unused media files
   - Delete custom pages if not needed
   - Remove theme-specific plugins

**Note:** Deleting the theme will remove all theme files but preserve your content (pages, posts, media).

---

## Additional Resources

### WordPress Documentation
- [WordPress Codex](https://codex.wordpress.org/)
- [WordPress Support Forums](https://wordpress.org/support/)
- [WordPress Theme Handbook](https://developer.wordpress.org/themes/)

### Theme Development
- [Theme Review Guidelines](https://make.wordpress.org/themes/handbook/review/)
- [WordPress Coding Standards](https://developer.wordpress.org/coding-standards/)

### Useful Plugins
- **Contact Form 7:** Contact forms
- **Yoast SEO:** SEO optimization
- **WP Super Cache:** Performance
- **UpdraftPlus:** Backups
- **Smush:** Image optimization
- **Wordfence:** Security

---

## Credits

**Theme Name:** Zierhofer Installateur  
**Version:** 3.0.0  
**Developer:** Black10998  
**Repository:** [https://github.com/Black10998/zierhofer-alkhala](https://github.com/Black10998/zierhofer-alkhala)  
**License:** GPL v2 or later  

**Original Website:** Sana Tec - Gas, Wasser und Heizung  
**Conversion:** Complete 1:1 WordPress theme from static HTML site  

---

## License

This theme is licensed under the GNU General Public License v2 or later.

```
Copyright (C) 2025 Black10998

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.
```

---

**Developed by Black10998**  
[https://github.com/Black10998/zierhofer-alkhala](https://github.com/Black10998/zierhofer-alkhala)

**Last Updated:** 2025-11-24
