"# Professional Portfolio Website - Harsh

Yeh ek modern aur professional portfolio website hai jo **HTML, CSS, JavaScript aur React** me banai gayi hai.

## 📁 Files Structure

```
portfolio_files/
├── index.html          # Complete HTML file (Standalone)
├── styles.css          # Custom CSS styling
├── script.js           # JavaScript for interactions
├── react/              # React Version
│   ├── App.js         # Main React Component
│   ├── App.css        # React Component Styles
│   ├── index.js       # React Entry Point
│   └── index.css      # Global React Styles
└── README.md          # Yeh file
```

## 🚀 Features

✅ **Modern & Professional Design** - Clean, attractive aur professional layout
✅ **Fully Responsive** - Mobile, tablet aur desktop par perfectly kaam karta hai
✅ **Smooth Animations** - Beautiful fade-in aur hover effects
✅ **Navigation Bar** - Sticky navigation with smooth scrolling
✅ **Hero Section** - Eye-catching introduction with CTA buttons
✅ **About Section** - Professional introduction with stats
✅ **Skills Section** - Organized skills with icons
✅ **Projects Showcase** - Portfolio projects with descriptions
✅ **Testimonials** - Client feedback section
✅ **Contact Section** - Clear contact information with call-to-action
✅ **Social Links** - GitHub, LinkedIn, Email aur Phone links
✅ **Scroll to Top Button** - Easy navigation back to top

## 🎨 Design Highlights

- **Color Scheme**: Blue & Purple gradients (professional & modern)
- **Typography**: Inter font family (clean & readable)
- **Icons**: Font Awesome 6.4.0
- **Framework**: Tailwind CSS (via CDN)
- **Responsive**: Mobile-first design approach

---

## 📖 Kaise Use Karein?

### Option 1: HTML Version (Standalone)

**Sabse Simple Way - Direct Open Karo:**

1. **Download karo** saari files (index.html, styles.css, script.js)
2. **Ek folder me rakho** teeno files ko
3. **index.html** file ko double-click karke browser me kholo
4. **That's it!** Website ready hai ✅

**Ya Hosting par upload karo:**
- cPanel/FileManager me upload karo
- GitHub Pages par host karo
- Netlify/Vercel par deploy karo

### Option 2: React Version

**Prerequisites:**
```bash
# Node.js aur npm installed hona chahiye
node --version
npm --version
```

**Setup Instructions:**

1. **React App Create Karo:**
```bash
npx create-react-app harsh-portfolio
cd harsh-portfolio
```

2. **Tailwind CSS Install Karo:**
```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init
```

3. **Tailwind Configuration:**

`tailwind.config.js` file me yeh add karo:
```javascript
module.exports = {
  content: [
    \"./src/**/*.{js,jsx,ts,tsx}\",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

4. **Files Copy Karo:**
```bash
# Portfolio files folder se copy karo
cp react/App.js src/App.js
cp react/App.css src/App.css
cp react/index.js src/index.js
cp react/index.css src/index.css
```

5. **Font Awesome Add Karo:**

`public/index.html` ke `<head>` section me add karo:
```html
<link rel=\"stylesheet\" href=\"https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css\">
```

6. **Run Karo:**
```bash
npm start
```

Website `http://localhost:3000` par open ho jayegi! 🎉

---

## 🛠️ Customization Guide

### Apni Information Add Karo:

#### 1. **Name Change:**
   - HTML: Line 32 (`<h1>Harsh</h1>`) ko apna naam se replace karo
   - React: App.js me search karo \"Harsh\" aur replace karo

#### 2. **Contact Details:**
   - **Email**: `harshwebtech09@gmail.com` → Apna email
   - **Phone**: `9555627513` → Apna phone number
   - **Location**: `India` → Apna location

#### 3. **Profile Image:**
   - HTML Line 125: `img src=\"...\"` me apni photo ka URL dalo
   - Ya local image use karo: `<img src=\"profile.jpg\">`

#### 4. **Social Links:**
   - GitHub: `https://github.com/yourusername`
   - LinkedIn: `https://linkedin.com/in/yourprofile`
   - Other social media links add kar sakte ho

#### 5. **Projects Update:**
   - Projects section me apne actual projects add karo
   - Project descriptions update karo
   - Technologies/tags change karo

#### 6. **Skills Modify:**
   - Skills section me apne skills add/remove karo
   - Services update karo according to what you offer

#### 7. **Colors Change (Optional):**
   
   **Blue → Green ke liye:**
   - `blue-600` → `green-600`
   - `purple-600` → `emerald-600`
   - `from-blue-400` → `from-green-400`

---

## 📱 Browser Support

✅ Chrome (Latest)
✅ Firefox (Latest)
✅ Safari (Latest)
✅ Edge (Latest)
✅ Mobile Browsers

---

## 💡 Tips

1. **SEO ke liye**: Meta tags add karo (title, description, keywords)
2. **Performance**: Images ko optimize karo (WebP format use karo)
3. **Analytics**: Google Analytics add kar sakte ho
4. **Forms**: Contact form add kar sakte ho (EmailJS ya FormSpree use karo)
5. **Portfolio Images**: Projects me actual screenshots add karo

---

## 🐛 Common Issues & Solutions

### Issue 1: Icons dikh nahi rahe
**Solution**: Font Awesome CDN link check karo `<head>` section me

### Issue 2: Styles apply nahi ho rahe
**Solution**: `styles.css` file same folder me hai ya nahi check karo

### Issue 3: Smooth scrolling kaam nahi kar raha
**Solution**: `script.js` file properly linked hai ya nahi check karo

### Issue 4: Mobile me responsive nahi hai
**Solution**: Viewport meta tag check karo:
```html
<meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\">
```

---

## 📞 Support

Agar koi problem ho ya customization me help chahiye, toh contact karo:
- Email: harshwebtech09@gmail.com
- Phone: +91 9555627513

---

## 📄 License

Yeh template free hai use karne ke liye! Apni projects me use kar sakte ho. 🎉

---

## 🙏 Credits

- **Design & Development**: Harsh
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Inter)
- **CSS Framework**: Tailwind CSS

---

## 🎯 Next Steps

1. ✅ Apni information add karo
2. ✅ Profile photo update karo
3. ✅ Actual projects add karo with screenshots
4. ✅ Social media links connect karo
5. ✅ Domain kharido aur website host karo
6. ✅ Business cards aur social media par share karo

**All the best for your web development journey! 🚀**
"