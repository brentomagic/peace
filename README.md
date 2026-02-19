# Workshop Website - Building Stronger Families

A professional website for marketing and managing your FAML445 workshop series.

## Website Structure

This website includes all required pages for your assignment:

- **index.html** - Home page with workshop overview
- **sessions.html** - Detailed breakdown of each workshop session
- **schedule.html** - Complete schedule, dates, times, location, directions, and map
- **contact.html** - Contact information and registration form
- **about.html** - About the facilitator page
- **styles.css** - Professional styling for all pages

## Assignment Requirements Checklist

✅ **Overview of what you are teaching** - Home page includes comprehensive overview
✅ **Overview of what each session will cover** - Sessions page details all 6 sessions
✅ **Date, time, and location of each class** - Schedule page includes complete table
✅ **Directions or map to the location** - Schedule page includes written directions and embedded Google Maps
✅ **Contact information** - Contact page with email, phone, and form
✅ **Additional marketing/logistical info** - Includes target audience, what to bring, parking info, accessibility

## Customization Needed

Before submitting, please customize the following with your actual information:

### 1. Contact Information (contact.html)
- Replace `workshop@example.com` with your actual email address
- Replace `(123) 456-7890` with your actual phone number (or remove if not applicable)

### 2. Workshop Details
- **Workshop Name**: Currently "Building Stronger Families Workshop" - update to your specific workshop name
- **Session Topics**: Update session titles and content in `sessions.html` to match your actual workshop curriculum
- **Dates & Times**: Update all dates and times in `sessions.html` and `schedule.html` to match your actual schedule

### 3. Location Information (schedule.html)
- Replace "Community Center - Room A" with your actual venue name and room
- Update the address: "123 Main Street, Downtown Area, City, State 12345"
- Update parking and transportation directions to match your actual location
- **IMPORTANT**: Update the Google Maps embed URL with your actual location coordinates

### 4. About Page (about.html)
- Update the facilitator bio with your actual background and experience
- Add a professional photo (replace the placeholder)
- Customize the approach and experience sections to reflect your actual work

### 5. Home Page (index.html)
- Update workshop description to match your specific topic
- Customize benefits and target audience sections
- Update facilitator credibility section

## Google Maps Setup

To add your actual location to the map:

1. Go to [Google Maps](https://www.google.com/maps)
2. Search for your workshop location
3. Click "Share" → "Embed a map"
4. Copy the iframe code
5. Replace the iframe in `schedule.html` (around line 120) with your actual map embed code

Alternatively, you can generate a map link:
- Use format: `https://www.google.com/maps/search/?api=1&query=YOUR+ADDRESS`
- Replace spaces with `+` signs

## Publishing Your Website

### Option 1: GitHub Pages (Free & Easy)

1. Create a GitHub account if you don't have one
2. Create a new repository (make it public)
3. Upload all HTML and CSS files to the repository
4. Go to Settings → Pages
5. Select "main" branch and "/ (root)" folder
6. Click Save
7. Your site will be live at: `https://yourusername.github.io/repository-name/`

### Option 2: Netlify (Free & Easy)

1. Go to [netlify.com](https://www.netlify.com)
2. Sign up for a free account
3. Drag and drop your project folder onto Netlify
4. Your site will be live immediately with a custom URL

### Option 3: Google Sites

1. Copy the content from each HTML page
2. Create a new Google Site
3. Paste content into appropriate pages
4. Use Google Sites' built-in map widget for the location

### Option 4: Other Platforms

- **Wix/Squarespace**: Copy content and recreate pages using their drag-and-drop editors
- **Your own web hosting**: Upload files via FTP to your hosting provider

## Testing Before Submission

Before submitting, verify:

- [ ] All navigation links work correctly
- [ ] Contact form opens email client (or update to use a form service like Formspree)
- [ ] Google Maps embed shows correct location
- [ ] All dates, times, and locations are accurate
- [ ] Contact information is correct
- [ ] Site is publicly accessible (not behind login)
- [ ] All pages load correctly on mobile devices

## Contact Form Note

The contact form currently uses a mailto link fallback. For a fully functional form, consider:

- **Formspree.io** (free tier available) - Add action URL to form
- **Google Forms** - Embed a Google Form instead
- **EmailJS** - Free JavaScript email service

## Mobile Responsiveness

The website is responsive and will work on mobile devices. Test on your phone to ensure everything displays correctly.

## Need Help?

If you need to customize specific sections or have questions about deployment, refer to the plan document or ask for assistance with specific customizations.

---

**Remember**: Make sure your website is publicly visible before submitting the link to your instructor!
