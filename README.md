# MRDU Forms

A GitHub Pages site for embedding Google Forms with a custom header image.

## 🌐 Live Site

Once GitHub Pages is enabled, your site will be available at:
`https://21f1002409.github.io/mrdu_forms/`

## 📝 Setup Instructions

### 1. Enable GitHub Pages

1. Go to your repository settings
2. Navigate to **Pages** section
3. Under **Source**, select the branch (usually `main` or `master`)
4. Click **Save**
5. Wait a few minutes for the site to be published

### 2. Configure Your Google Form

1. Open your Google Form
2. Click the **Send** button (top right)
3. Click the **Embed** icon (`<>`)
4. Copy the entire iframe code or just the `src` URL

### 3. Update the Embed Code

Edit `index.html` and replace the placeholder URL in the iframe:

```html
<iframe 
    src="YOUR_GOOGLE_FORM_EMBED_URL_HERE" 
    frameborder="0" 
    marginheight="0" 
    marginwidth="0">
    Loading…
</iframe>
```

### 4. Customize the Header Image (Optional)

Replace `header-image.svg` with your own image:
- Supported formats: JPG, PNG, SVG, GIF
- Recommended size: 1200x300 pixels
- Update the filename in `index.html` if you use a different name

### 5. Customize the Page Content

Edit `index.html` to update:
- Page title: `<title>MRDU Forms</title>`
- Header text: `<h1>MRDU Forms</h1>`
- Description: `<p>Please fill out the form below</p>`
- Footer text: `<p>&copy; 2025 MRDU Forms. All rights reserved.</p>`

## 📁 Files

- `index.html` - Main HTML file for the GitHub Pages site
- `header-image.svg` - Sample header image (replace with your own)
- `README.md` - This file

## 🎨 Features

- ✅ Responsive design (works on mobile and desktop)
- ✅ Clean, modern layout
- ✅ Custom header image
- ✅ Embedded Google Forms
- ✅ Professional styling

## 🛠️ Troubleshooting

**Form not loading?**
- Make sure you copied the correct embed URL from Google Forms
- Ensure the form is set to accept responses
- Check that the form sharing settings allow public access

**Page not showing?**
- Wait 5-10 minutes after enabling GitHub Pages
- Check the Pages section in repository settings for deployment status
- Ensure `index.html` is in the root directory

## 📱 Browser Compatibility

This site works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## 📄 License

Free to use and modify as needed.
