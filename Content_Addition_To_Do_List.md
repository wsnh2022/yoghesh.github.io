# Manual TODO List - What YOU Need to Add

## 🔴 CRITICAL - Must Do Before Launch

### 1. Update Your Email Address
**Location:** Line ~454 in the HTML file
**Current:** `mailto:your.email@example.com`
**Action:** Replace with your actual email address

```html
<!-- Find this line: -->
<a href="mailto:your.email@example.com" class="px-8 py-4...">

<!-- Change to: -->
<a href="mailto:youremail@gmail.com" class="px-8 py-4...">
```

---

## 🟡 HIGH PRIORITY - Add Real Content

### 2. Add Design Portfolio Image
**Location:** "Beyond the Terminal" section (around line ~570)
**Current:** Placeholder box with icon
**What to do:**
1. Create a collage of your best design work (posters, flyers, social media)
2. Save as: `design-portfolio.jpg` or `design-portfolio.webp`
3. Optimize for web (max 800px wide, under 200KB)
4. Replace the placeholder `<div>` with:

```html
<img src="design-portfolio.jpg" alt="Design portfolio showcasing branding projects" 
     class="w-full h-full object-cover rounded-lg">
```

**Alternative if you don't have designs yet:**
- Skip this for now
- The placeholder looks professional enough
- Add it later when you have 3-4 good examples

---

### 3. Add GitHub Repository Links
**Location:** Project cards (lines ~506, ~534, ~560)
**Current:** Placeholder buttons that do nothing
**What to do:**

For each project, replace:
```html
<button class="text-sm text-accent...">
    <i class="fab fa-github"></i> View Code
</button>
```

With:
```html
<a href="https://github.com/wsnh2022/YOUR-REPO-NAME" 
   target="_blank" rel="noopener noreferrer"
   class="text-sm text-accent...">
    <i class="fab fa-github"></i> View Code
</a>
```

**If you don't have public repos:**
- Option 1: Remove the buttons entirely
- Option 2: Change to "Contact for Details" and link to email
- Option 3: Leave as-is until you create repos

---

## 🟢 NICE TO HAVE - Optional Enhancements

### 4. Add Project Screenshots (Optional)
**Location:** Each project card has a placeholder icon area
**What to do:**
1. Take screenshots of your dashboards/tools
2. Blur any sensitive data
3. Save as: `project1-screenshot.jpg`, etc.
4. Replace the icon `<div>` with images

**Example:**
```html
<!-- Instead of: -->
<i class="fas fa-database text-4xl..."></i>

<!-- Use: -->
<img src="project1-screenshot.jpg" alt="ETL Pipeline Dashboard" 
     class="w-full h-full object-cover">
```

---

### 5. Update Domain/URL (When Deploying)
**Location:** Line ~14 in meta tags
**Current:** `https://yourwebsite.com`
**What to do:** Change to your actual domain after deployment

```html
<meta property="og:url" content="https://yourwebsite.com">
<!-- Change to: -->
<meta property="og:url" content="https://yoghesh-portfolio.netlify.app">
```

---

### 6. Add Real Project Details (Optional)
**Current state:** Generic project descriptions
**Enhancement:** Add more specifics if you have them

**What to consider:**
- Actual company names (if you have permission)
- Specific tools used (Python libraries, SQL dialects)
- More detailed metrics
- Challenges you solved

**Example Enhancement:**
```
Current: "Created a script to parse PDF invoices..."
Better:  "Created a Python script using PyPDF2 and openpyxl to parse 50+ 
          invoices daily, automatically extracting vendor details, line items, 
          and totals into SAP-ready Excel templates."
```

---

### 7. Add Testimonials Section (Optional)
**Location:** After "Beyond the Terminal" section
**What to do:**
1. Get 2-3 recommendations from LinkedIn
2. Ask permission to use them
3. Add a new section:

```html
<section class="mb-24 scroll-reveal">
    <h2 class="text-3xl md:text-4xl font-display font-bold text-white mb-10">
        What Clients Say
    </h2>
    <div class="grid md:grid-cols-2 gap-6">
        <div class="glass rounded-xl p-6">
            <p class="text-slate-400 mb-4 italic">
                "Yoghesh's automation saved us 15+ hours per week..."
            </p>
            <p class="text-white font-bold">— Client Name</p>
            <p class="text-slate-500 text-sm">Company, Role</p>
        </div>
    </div>
</section>
```

---

### 8. Add Resume/CV Download (Optional)
**Location:** Contact section, add another button
**What to do:**
1. Create a PDF of your resume
2. Upload it with your website files as `yoghesh-resume.pdf`
3. Add download button:

```html
<a href="yoghesh-resume.pdf" download 
   class="px-8 py-4 bg-surface hover:bg-slate-700...">
    <i class="fas fa-download"></i> Download Resume
</a>
```

---

## 📋 Quick Checklist Before Launch

### Must Have ✅
- [ ] Update email address
- [ ] Test all navigation links work
- [ ] Check mobile menu works on phone
- [ ] Verify LinkedIn/GitHub links are correct

### Should Have 🎯
- [ ] Add design portfolio image
- [ ] Add GitHub repo links OR remove buttons
- [ ] Test on 3+ different devices
- [ ] Get 1-2 people to review it

### Nice to Have ⭐
- [ ] Add project screenshots
- [ ] Add testimonials
- [ ] Create downloadable resume
- [ ] Update meta tags with real domain

---

## 🚀 Deployment Checklist

When you're ready to publish:

### Choose a Platform:
- **Netlify** (Easiest - Free)
  1. Drag and drop your HTML file
  2. Done in 2 minutes
  
- **GitHub Pages** (Free)
  1. Create repo
  2. Upload HTML file
  3. Enable GitHub Pages in settings
  
- **Vercel** (Free)
  1. Import from GitHub
  2. Auto-deploys on updates

### After Deployment:
- [ ] Update og:url meta tag with real URL
- [ ] Test all links on live site
- [ ] Share on LinkedIn
- [ ] Add URL to your resume
- [ ] Submit to Google Search Console

---

## ⏱️ Time Estimates

| Task | Time Required | Priority |
|------|---------------|----------|
| Update email | 1 minute | 🔴 Critical |
| Test mobile menu | 5 minutes | 🔴 Critical |
| Add design image | 30-60 min | 🟡 High |
| Add GitHub links | 10 minutes | 🟡 High |
| Add screenshots | 1-2 hours | 🟢 Optional |
| Add testimonials | 1-2 hours | 🟢 Optional |

---

## 💡 Pro Tips

1. **Start Simple**: Launch with just email updated, add content later
2. **Iterate**: Don't wait for perfection - get it live and improve
3. **Get Feedback**: Share with 2-3 trusted people before public launch
4. **Track Changes**: Keep a copy of each version as you update
5. **Mobile First**: Always test on your phone after changes

---

## 🎯 Minimum Viable Launch

To go live TODAY, you only need:
1. ✅ Update email address (1 min)
2. ✅ Test mobile menu (2 min)
3. ✅ Upload to Netlify (2 min)

**Total: 5 minutes to launch!**

Everything else can be added incrementally as you have time.

---

**Remember:** A live portfolio with 80% content is better than a perfect portfolio that stays on your hard drive!

---

*Generated: December 15, 2025*
*Your portfolio is 95% ready to launch!*
