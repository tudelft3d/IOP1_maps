# IOP1 Maps Collection

A website that automatically displays interactive maps created by students. 

## 📁 Project Structure

```
IOP1_maps/
├── maps/                    # Student map directories
│   ├── 012345/             # Example: Student ID or project name
│   │   ├── index.html      # Main map file
│   │   └── ...             # Additional files (CSS, JS, images)
│   └── [student-id]/       # Each student gets their own directory
├── themes/simple-maps/      # Hugo theme
├── content/                 # Hugo content
├── static/                  # Static files (maps are copied here)
├── .github/workflows/       # GitHub Actions for deployment
└── hugo.toml               # Hugo configuration
```

## 🎯 For Students: How to Submit Your Map

1. **Fork this repository** to your GitHub account
2. **Clone your fork** locally
3. **Create your map directory** in the `static/maps/` folder using your student ID or project name:
   ```bash
   mkdir maps/your-student-id
   ```
4. **Add your map files**:
   - Your main map file must be named `index.html`
   - Add any CSS, JavaScript, images, or other assets to your directory
   - Test your map by opening `static/maps/your-student-id/index.html` in a browser
5. **Commit and push** your changes:
   ```bash
   git add maps/your-student-id/
   git commit -m "Add map for student [your-id]"
   git push origin main
   ```
6. **Create a Pull Request** from your fork to the main repository
7. **Wait for approval** - once merged, your map will automatically appear on the website!
