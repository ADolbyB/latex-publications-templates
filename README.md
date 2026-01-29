<div align="center">

# LaTeX Publications & Templates
### Your Ultimate LaTeX Learning Ecosystem

[![Stars](https://img.shields.io/github/stars/ADolbyB/latex-publications-templates?style=for-the-badge&logo=github)](https://github.com/ADolbyB/latex-publications-templates/stargazers)
[![Forks](https://img.shields.io/github/forks/ADolbyB/latex-publications-templates?style=for-the-badge&logo=github)](https://github.com/ADolbyB/latex-publications-templates/network/members)
[![Issues](https://img.shields.io/github/issues/ADolbyB/latex-publications-templates?style=for-the-badge&logo=github)](https://github.com/ADolbyB/latex-publications-templates/issues)
[![GitHub License](https://img.shields.io/github/license/ADolbyB/latex-publications-templates?style=for-the-badge&logo=github)](https://github.com/ADolbyB/latex-publications-templates/blob/main/LICENSE)



[![Last Commit](https://img.shields.io/github/last-commit/ADolbyB/latex-publications-templates?style=for-the-badge&logo=github)](https://github.com/ADolbyB/latex-publications-templates/commits)
[![Repo Size](https://img.shields.io/github/repo-size/ADolbyB/latex-publications-templates?style=for-the-badge&logo=github)](https://github.com/ADolbyB/latex-publications-templates)
[![Top Language](https://img.shields.io/github/languages/top/ADolbyB/latex-publications-templates?style=for-the-badge)](https://github.com/ADolbyB/latex-publications-templates)

**LaTeX** | **Academic Publishing** | **Templates** | **Tutorials**

</div>

---

## 🚀 What Is This Repository?

**LaTeX Publications & Templates** is a **curated, battle-tested LaTeX knowledge base** built from real-world usage, actual publications, and production workflows. This is not just another collection of `.tex` files—it's a comprehensive learning ecosystem designed to help students, engineers, researchers, and technical writers master LaTeX.

**Inside you'll find:**

✅ **Real publications** written in LaTeX with complete source code  
✅ **Professional templates** ready to compile and customize  
✅ **Beginner-to-intermediate tutorials** for rapid skill development  
✅ **Environment setup guides** for VS Code, MiKTeX, and Overleaf  
✅ **High-quality external resources** carefully curated and organized  

> 📌 Everything is structured to minimize fluff and maximize learning speed. Learn by example, not guesswork.

---

## 🏆 Why This Repository Is Worth Your Time

### 📘 Learn from Real Publications

Unlike generic guides, this repo includes **actual LaTeX source from published documents**. These examples demonstrate:

- Professional document structure and formatting
- Proper bibliography management with BibTeX
- Figures, tables, equations, and cross-references
- Clean formatting that meets academic standards
- IEEE conference paper formatting
- Technical documentation best practices

**If you've ever wondered *"How do real papers do this?"* — this is your answer.**

### ⚡ Production-Ready Templates

All templates are:
- ✅ **Ready to compile** out of the box
- ✅ **Cleanly structured** for easy modification
- ✅ **Standards-compliant** (IEEE, academic, technical)
- ✅ **Organized logically** with clear file hierarchy

### 🎯 Practical Learning Path

This repository provides a **structured learning progression**:
1. Browse compiled PDF examples
2. Study source code structure
3. Use templates for your own work
4. Learn advanced techniques from tutorials
5. Build confidence with real projects

---

## 📥 Download My LaTeX Publications

Explore complete LaTeX projects with compiled PDFs and full source code:

**From Crisis To Control** : IEEE conference-style LaTeX publication demonstrating professional formatting and structure

[![PDF - From Crisis To Control](https://img.shields.io/badge/PDF-From_Crisis_To_Control-blue?style=for-the-badge&logo=latex&logoColor=white)](https://github.com/ADolbyB/latex-publications-templates/releases/latest/download/CrisisToControl.pdf)

**General Handheld Radio Primer** — Complete technical documentation with figures, tables, and references

[![PDF - General Handheld Radio Primer](https://img.shields.io/badge/PDF-General_Handheld_Radio_Primer-blue?style=for-the-badge&logo=latex&logoColor=white)](https://github.com/ADolbyB/latex-publications-templates/releases/latest/download/2025_HT1000_ch_guide.pdf)

**Tutorial PDFs** : Download Precompiled PDFs

[![Releases](https://img.shields.io/badge/Releases-Download_PDFs-blue?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ADolbyB/latex-publications-templates/releases)

**Each publication demonstrates:**
- Clean document organization
- Package management strategies
- Professional typography and formatting
- Reusable components and structure
- Best practices in technical writing

> 💡 Open the source files to see exactly how these documents were created.

---

## 📂 Repository Structure

```
latex-publications-templates/
├── Publications/               # Real LaTeX publications source  
│   ├── Articles/               # Technical documentation example  
│   └── Conference/             # Technical documentation example  
│       ├── Backup/             # Backup copy of CrisistoControl.tex (renamed SNSS-Backup.tex)  
│       └── DisasterMgmt/       # IEEE disaster managment paper example  
├── Tutorials/                  # Curated learning resources  
│   ├── 00a-Tutorial1/          # Basic document compilation  
│   ├── 00b-MLACites/           # Using MLA citations  
│   ├── 00c-UsingBibTex/        # Using example book chapters w/ BibTex  
│   ├── 01-FCC-BasicStructure/  # Basic document structure  
│   ├── 02-FCC-BasicMath/       # Basic use of mathematical equations
│   ├── 03-FCC-TablesArrays/    # Brackets, Tables and Arrays
│   ├── 04-FCC-Lists/           # Using different types of lists
│   ├── 05-FCC-Formatting/      # Text and Document Formatting
│   ├── 06-FCC-MacrosGraphics/  # Packages, Macros and Graphics
│   ├── 07-FCC-Debuggings/      # Debugging techniques
│   ├── 08-FCC-Calculus/        # Calculus math notation
│   ├── 09-FCC-MathPaper/       # IB Mathematics SL Internal Assessment template
│   ├── 10-FCC-BeamerPPT/       # LaTeX Beamer Tutorial
│   ├── 11a-IEEE-Conference/    # Example IEEE paper with title.
│   ├── 11b-IEEE-withBib/       # Example IEEE used by author for CrisisToControl.pdf
│   ├── 12-LabelError/          # Some Debug techniques
│   └── 13-imageFlipping/       # External links and references
└── README.md                   # You are here
```

---

## 🛠️ Environment Setup

Choose your LaTeX workflow based on your preferences and needs.

### 💻 Local Development (Recommended for Power Users)

**Option 1: VS Code on Linux Mint**

1. **Install VS Code** - [Download VS Code](https://code.visualstudio.com/)
   - Lightweight and fast
   - Excellent LaTeX support

2. **Add LaTeX Workshop Extension**
   - [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
   - Auto-compilation on save
   - PDF preview in editor
   - Syntax highlighting and IntelliSense

3. Add all LaTeX packages to your installation: 
```bash
sudo apt update
sudo apt install texlive-publishers texlive-science texlive-fonts-recommended texlive-latex-extra texlive-bibtex-extra
```

**Why this setup?**
- ✅ Fastest compilation
- ✅ Full control over packages
- ✅ Works offline
- ✅ Git-friendly workflow

**Option 2: TeXMaker (Standalone Editor)**

- **Install** - [Download TeXMaker](https://www.xm1math.net/texmaker/)
- Dedicated LaTeX IDE
- Built-in PDF viewer
- Still requires `texlive` packages above for PDF compilation

### ☁️ Online Editing (Great for Beginners & Collaboration)

**Overleaf** - [Visit Overleaf](https://www.overleaf.com/)

**Advantages:**
- ✅ Zero local setup required
- ✅ Browser-based compilation
- ✅ Real-time collaboration
- ✅ Perfect for teams and classrooms
- ✅ Automatic package management
- ✅ Built-in version control

**Perfect for:**
- Students new to LaTeX
- Collaborative writing projects
- Quick document creation
- Cloud-based workflows

---

## 📚 Learning Resources

### 🎥 Video Tutorials

| Resource | Description | Link |
|----------|-------------|------|
| **LaTeX for Beginners** | Comprehensive introduction to LaTeX | [Electrical Engineering Lectures](https://www.youtube.com/watch?v=1bB8kOgkWTA) |
| **VS Code LaTeX Setup** | Complete guide to compiling LaTeX in VS Code | [Simulation Engineer](https://simulation.engineer/latex-compile-vscode) |
| **LaTeX Full Course** | In-depth beginner to intermediate tutorial | [FreeCodeCamp](https://www.freecodecamp.org/news/learn-latex/) |
| **Michelle Krummel Series** | High-quality LaTeX tutorial playlist | [YouTube Channel](https://www.youtube.com/channel/UC6mURe9lQHTBQkpSCPr1OBg) |

### 📄 Written Guides & Documentation

| Resource | Description | Link |
|----------|-------------|------|
| **IEEE Templates** | Official manuscript templates for conference proceedings | [IEEE Publishing](https://www.ieee.org/conferences/publishing/templates.html) |
| **Overleaf Gallery** | Extensive template collection (thesis, articles, CVs) | [Overleaf Templates](https://www.overleaf.com/gallery) |
| **LaTeX Templates** | Curated collection of professional templates | [LaTeXTemplates.com](https://www.latextemplates.com/) |
| **IEEE Citation Generator** | Quick citation tool for IEEE format | [MyBib](https://www.mybib.com/tools/ieee-citation-generator) |

---

## 📦 Getting Started

### ⚡ Quick Start

```bash
git clone https://github.com/ADolbyB/latex-publications-templates.git
cd latex-publications-templates
code .

# All PDFs are already generated into the Releases section of this repository.
```

### 📝 Using Templates  

1. **Choose a template** from `Publications\` or `Tutorials\`  
2. **Copy the template** to your working directory  
3. **Modify** the content while preserving structure  
4. **Compile** using your preferred method  
5. **Iterate** until satisfied with results  

### 🔍 Learning from Publications  

1. **Browse** the compiled PDFs in `Publications/`  
2. **Open** the corresponding source `.tex` files  
3. **Study** the document structure and packages used  
4. **Experiment** by modifying and recompiling  
5. **Apply** techniques to your own documents  

### 📥 Download Precompiled PDFs  

  [![Releases](https://img.shields.io/badge/Releases-Download_PDFs-blue?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ADolbyB/latex-publications-templates/releases)  

---

## 🧠 Practical LaTeX Tips  

Even experienced LaTeX users forget these fundamentals:

| Tip | Why It Matters |
|-----|----------------|
| ✅ **Use `.bib` files** | Clean, scalable citations that auto-format |
| ✅ **Split large documents** | Multiple `.tex` files improve readability |
| ✅ **Prefer vector graphics** | PDFs and SVGs scale perfectly |
| ✅ **Use version control** | Git + LaTeX = perfect collaboration |
| ✅ **Comment your code** | Future you will thank present you |
| ✅ **Compile multiple times** | References need 2-3 passes to resolve |
| ✅ **Keep packages minimal** | Only load what you actually use |
| ✅ **Use semantic commands** | `\emph{}` not `\textit{}` for meaning |

These small habits make a **massive difference** in long-term productivity.

---

## 📊 Template Categories  

### 📄 IEEE Conference Papers  
- Single-column and double-column formats
- Proper citation styles
- Figure and table examples
- Ready for submission

### 🎓 Academic Documents  
- Thesis and dissertation templates
- Research reports
- Class notes and documentation
- CVs and resumes

### 📊 Presentations  
- Beamer slide decks
- Professional themes
- Code highlighting
- Mathematical notation

### 📃 Technical Documentation  
- User manuals
- API documentation
- Technical reports
- White papers

---

## 🤝 Contributing

This repository is designed to **grow and evolve** with community input.

**You're encouraged to:**

- ⭐ **Star** the repository if it helps you
- 🍴 **Fork** and add new templates or examples
- 🐛 **Report issues** with existing templates
- 📚 **Share** tutorials and learning resources
- 💡 **Suggest** improvements or new features
- 📝 **Contribute** your own LaTeX publications (optional)

**How to contribute:**

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-template`)
3. Commit your changes (`git commit -m 'Add new IEEE template'`)
4. Push to the branch (`git push origin feature/new-template`)
5. Open a Pull Request

LaTeX gets better when the community builds together.

---

## 🧪 Topics & Technologies

This repository covers:

```
📌 LaTeX           📌 Academic Writing    📌 IEEE Publishing
📌 BibTeX          📌 Technical Docs      📌 Beamer Presentations
📌 VS Code         📌 MiKTeX              📌 Overleaf
📌 PDF Generation  📌 Document Templates  📌 Research Papers
```

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/ADolbyB/latex-publications-templates/blob/main/LICENSE.md) file for details.

**For templates and publications:**
- Use freely for academic and personal projects
- Attribution appreciated but not required
- Modify as needed for your use case

---

## ✨ Final Thought

If you want to **write cleaner papers**, **submit better publications**, and **understand LaTeX instead of fighting it**, this repository was built for you.

**Stop wrestling with formatting. Start focusing on content.**

> ⚡ This is not a toy repo. Everything here reflects **real LaTeX used in production**.

---

<div align="center">

**Master LaTeX. Write Better. Publish Confidently.**

Happy typesetting! 📚✨

[![GitHub](https://img.shields.io/badge/Follow-ADolbyB-blue?style=for-the-badge&logo=github)](https://github.com/ADolbyB)

</div>