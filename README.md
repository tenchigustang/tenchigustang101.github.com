# tenchigustang101.github.com
# Tech History Archive - GitHub Pages Website

A complete, professional static website celebrating vintage computers, legendary programmers, and tech milestones. Perfect for creating valuable backlinks to TechGeeks Apparel while providing genuine value to tech enthusiasts.

## 📁 Files Included

- `index.html` - Homepage with featured articles
- `vintage-computers.html` - Articles about classic computers (Apple II, IBM PC, Commodore 64)
- `legendary-programmers.html` - Profiles of computing pioneers (Alan Turing, Grace Hopper)
- `tech-milestones.html` - Historical tech achievements (Apollo Computer, Birth of Internet)
- `about.html` - About page with mission and values
- `README.md` - This file

## 🚀 How to Set Up on GitHub Pages

### Step 1: Create a New GitHub Repository

1. Go to https://github.com and log in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name it something like: `tech-history-archive` or `vintage-tech-blog`
5. Make it **Public**
6. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**
1. In your new repository, click "Add file" → "Upload files"
2. Drag and drop all 5 HTML files (index.html, vintage-computers.html, legendary-programmers.html, tech-milestones.html, about.html)
3. Click "Commit changes"

**Option B: Using Git Command Line**
```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
# Copy all HTML files to this directory
git add .
git commit -m "Initial commit - Tech History Archive website"
git push origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository's "Settings" tab
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait a few minutes - your site will be live at: `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

## ✏️ How to Customize

### Edit Social Media Links

All social media links are in the footer section of each HTML file. Look for this section:

```html
<div class="social-links">
    <h3>Connect With Us</h3>
    <div class="social-icons">
        <!-- EDIT THESE LINKS -->
        <a href="https://twitter.com/techgeeksapparel" ...>
        <a href="https://facebook.com/techgeeksapparel" ...>
        <!-- etc -->
    </div>
</div>
```

Replace the URLs with your actual social media profiles. You can:
- Add more social icons by copying the `<a>` tag pattern
- Remove social icons you don't need
- Change the emoji/symbols in the `<span>` tags

### Edit TechGeeks Apparel Links

The main apparel links appear in multiple places:
1. **Homepage**: In the "About Section" 
2. **Each article page**: In the "apparel-cta" boxes
3. **Footer**: In multiple locations

Search for `https://techgeeksapparel.com` in each file and verify all links are correct.

### Add More Articles

To add new articles to any page:

1. Open the relevant HTML file (e.g., `vintage-computers.html`)
2. Find the section with `<article id="..." class="article-full">`
3. Copy an existing article block
4. Update the content, ID, title, and text
5. Update links on the homepage to point to your new article

### Change Colors

All colors are defined at the top of each file in the `:root` section:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #e74c3c;
    --accent-color: #3498db;
    /* etc */
}
```

Change these hex codes to customize the color scheme.

## 🔗 SEO & Backlink Strategy

### Built-in Features

✅ **Multiple TechGeeks Apparel Links**
- Homepage: About section + footer
- Each article page: CTA boxes + footer
- All pages: Navigation footer links

✅ **Quality Content**
- Detailed, well-researched articles
- Original writing about tech history
- Valuable to readers (not just for backlinks)

✅ **Professional Design**
- Clean, modern layout
- Mobile responsive
- Fast loading (no external dependencies)

### Tips for Maximum SEO Value

1. **Link from TechGeeks Apparel**: Add a "Blog" or "Tech History" link on your main website pointing to this GitHub Pages site

2. **Social Media**: Share articles on Twitter, LinkedIn, Reddit (r/vintagecomputing, r/retrobattlestations)

3. **Add More Content**: Regularly add new articles to keep the site fresh

4. **Internal Linking**: Articles already link to each other - this helps SEO

5. **Submit to Search Engines**: 
   - Google Search Console
   - Bing Webmaster Tools

## 📊 Analytics (Optional)

To track visitors, add Google Analytics:

1. Get a Google Analytics tracking code
2. Add this before the closing `</head>` tag in each HTML file:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

## 🎨 Features

- ✅ Fully responsive (works on mobile, tablet, desktop)
- ✅ No external dependencies (works offline)
- ✅ Fast loading
- ✅ Clean, professional design
- ✅ Easy to edit and customize
- ✅ SEO-friendly structure
- ✅ Multiple backlinks to TechGeeks Apparel
- ✅ Genuine, valuable content

## 📝 Content Summary

**Vintage Computers**
- Apple II article (~1,500 words)
- IBM PC article (~1,200 words)
- Commodore 64 article (~1,300 words)

**Legendary Programmers**
- Alan Turing profile (~1,800 words)
- Grace Hopper profile (~1,700 words)

**Tech Milestones**
- Apollo Guidance Computer (~1,600 words)
- Birth of the Internet (ARPANET) (~1,500 words)

## 🛠️ Troubleshooting

**Site not showing up?**
- Make sure GitHub Pages is enabled in Settings
- Wait 5-10 minutes after enabling
- Check that `index.html` is in the root directory

**Links not working?**
- All internal links use relative paths
- Make sure file names are exactly as written (case-sensitive)

**Want to use a custom domain?**
- Add a CNAME file with your domain name
- Configure DNS records at your domain registrar
- See: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## 📧 Support

If you need help or have questions, feel free to open an issue in the GitHub repository.

## 📄 License

This website template is provided as-is for your use. Feel free to modify and customize as needed.

---

**Built for TechGeeks Apparel** | Celebrating vintage computing and tech history
