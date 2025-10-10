# Student Project Gallery - Setup Instructions

## 🎯 What This Is
A showcase of students' HTML projects. Each student has their own page accessible via a clean URL.

---

## 📁 File Structure

```
yourclassname/gallery/
│
├── index.html                    (Main gallery page)
│
└── students/                     (All student projects go here)
    ├── jules/
    │   └── index.html           (Jules's project)
    ├── jahnavi/
    │   └── index.html           (Jahnavi's project)
    └── alexis/
        └── index.html           (Alex's project)
```

---

## 🔗 Updating the Gallery Page

After adding a new student, update the main `index.html`:

1. Open `index.html` in your repository
2. Click the pencil icon (✏️) to edit
3. Find the gallery section (around line 115)
4. Copy one of the existing project cards:

```html
<a href="students/new-student-name/index.html" class="project-card">
    <div class="student-name">Student Name</div>
    <div class="project-title">Their Project Title</div>
    <span class="view-project">View Project →</span>
</a>
```

5. Change the path, name, and title
6. Click **"Commit changes"**
7. Wait 1-2 minutes for GitHub Pages to update

---

## 🎨 Customization Tips

### Change the Color Scheme
In `index.html`, find this section around line 16:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```
Replace the colors with your school colors!

### Change the Title
Line 8: `<title>Student Project Gallery</title>`
Line 92: `<h1>🎨 Student Project Gallery</h1>`

---

## 📝 Student Submission Workflow

### Option A: Students Submit Files to You
1. Students send their HTML file via  Canvas learning management system
2. Teacher uploads to the appropriate student folder on GitHub
3. Update the main gallery page with the project card

### Option B: Students Learn GitHub (Advanced)
1. Get to know Git basics
2. Fork this repository
3. Add your own project
4. Submit a pull request
5. Teacher review and merge

---

## ⚠️ Common Issues & Solutions

**Problem: Page shows 404 error**
- Wait 5 minutes after enabling GitHub Pages
- Make sure your repository is Public
- Check that files are in the main branch

**Problem: Student page is blank**
- Verify the file is named `index.html` (lowercase)
- Check that the path in the gallery matches the folder name
- Open the file and make sure it has actual HTML content

**Problem: Styles not working**
- If student has separate CSS file, make sure it's in the same folder
- Check that the CSS file path in their HTML is correct (relative path)

**Problem: Images not showing**
- Images must be in the student's folder
- Use relative paths: `<img src="photo.jpg">` not `<img src="C:/Users/...">`

---

## 🔒 Privacy & Safety

- Don't use student last names in folder names (use first name + initial)
- Review all student content before publishing
- Consider password-protecting the repository if needed (requires GitHub Premium)
- Remind students not to include personal information

---

## 💡 Pro Tips

1. **Naming Convention**: Use `firstname-lastinitial` for folders (e.g., `john-d`)
2. **Backups**: GitHub automatically keeps version history
3. **Mobile-Friendly**: The gallery is responsive and works on phones/tablets
4. **Offline Preview**: Open `index.html` in a browser to test before uploading
5. **Bulk Updates**: You can clone the repository to your computer and use Git for faster updates

---

## 📧 Need Help?

If you run into issues:
1. Check GitHub's documentation: https://pages.github.com
2. Search for "GitHub Pages" tutorials on YouTube

---

## 🎓 Educational Benefits

This project teaches students:
- How their work can be shared online
- Basic file organization
- The concept of URLs and web hosting
- (Optional) Git and version control basics
