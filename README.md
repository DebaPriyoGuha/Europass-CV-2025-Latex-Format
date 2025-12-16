# 📄 Europass CV Template (LaTeX)

A clean, professional Europass-style CV template built with LaTeX. Perfect for academic applications, Erasmus scholarships, and European job applications.

![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 📸 Preview

![Europass CV Preview](preview.pdf)

---

## 🚀 Quick Start Guide

Follow these simple steps to create your own Europass CV in less than 10 minutes!

### Step 1: Download the Files

Download these two files and put them in the **same folder**:
- `main.tex` (the template file)
- `europass_logo.png` (the Europass logo)

### Step 2: Add Your Profile Picture

- Take your profile photo
- Rename it to `profile_pic.jpg`
- Put it in the **same folder** as the other files

> 💡 **Tip:** Use a professional, passport-style photo for best results!

### Step 3: Open in LaTeX Editor

Use any LaTeX editor on your computer:
- [TeXstudio](https://www.texstudio.org/) (Recommended for beginners)
- [TeXmaker](https://www.xm1math.net/texmaker/)
- [VS Code](https://code.visualstudio.com/) with LaTeX Workshop extension
- [Overleaf](https://www.overleaf.com/) (Online, no installation needed)

### Step 4: Edit the Template

Open `main.tex` and replace the placeholder information with your own:
- Name
- Contact details
- Education
- Research experience
- Skills
- etc.

### Step 5: Use AI to Speed Up! 🤖

Want to make it even faster? Use any AI assistant (ChatGPT, Claude, etc.):

1. Give the AI this template
2. Paste your current CV or resume
3. Ask: *"Convert my CV to match this Europass template format"*
4. Copy the AI's output into your `main.tex` file

### Step 6: Compile and Done! ✅

Click the **Compile** or **Build** button in your LaTeX editor. Your beautiful Europass CV is ready!

---

## 🌐 View Online (No Installation)

Don't want to install anything? View and edit directly on Overleaf:

👉 **[Open in Overleaf](https://www.overleaf.com/read/sgdychjnqncr#d0e5f6)**

> **Note:** Click "Copy Project" to make your own editable version.

---

## 📁 File Structure
your-folder/
├── main.tex # Main template file (edit this!)
├── europass_logo.png # Europass logo
├── profile_pic.jpg # Your profile picture
└── README.md # This file

text

---

## ✨ Features

- ✅ Clean Europass-style design
- ✅ Professional circular profile picture with colored border
- ✅ Organized sections with blue dot markers
- ✅ Language skills table (CEFR levels)
- ✅ Clickable links (email, LinkedIn, GitHub, etc.)
- ✅ Easy to customize colors
- ✅ Print-friendly layout

---

## 🎨 Customization

### Change Colors

Find these lines at the top of `main.tex` and change the RGB values:

```latex
\definecolor{euroblue}{RGB}{14, 65, 148}      % Main blue color
\definecolor{euroaqua}{RGB}{96, 150, 183}     % Accent color (profile circle)
Change Profile Picture Border Color
Find this line and change euroaqua to any color you defined:

latex
\draw[euroaqua, line width=2.5pt] (0,0) circle (1.6cm);
