# Cursor AI Project Context

## 📚 Project Overview
This is a **Universal LaTeX Academic Notes Template** repository. This template provides an optimized LaTeX structure for creating academic notes across different courses and subjects.

## 🎯 Purpose
- **Template-based**: Reusable LaTeX structure for consistent note-taking
- **Multi-course**: Adaptable for any academic subject
- **Math-friendly**: Pre-configured for mathematical formulas and algorithms
- **Optimized Layout**: Compact margins and spacing for maximum content density

## 📁 File Structure
```
course-notes/
├── template.tex              # Main LaTeX template file
├── .gitignore               # LaTeX build files exclusions
├── .vscode/
│   └── settings.json        # VSCode LaTeX Workshop configuration
├── cursor.md               # This file - AI context
├── README.md               # Human-readable documentation
└── [date-folders]/         # Individual lecture notes (e.g., 2025-01-15/)
    ├── [date]-notes.tex    # Lecture-specific notes
    ├── [date]-notes.pdf    # Compiled PDF
    └── images/             # Lecture images/diagrams
```

## 🔧 Technical Configuration

### LaTeX Setup
- **Engine**: pdflatex (preferred) or latexmk
- **Packages**: amsmath, amsfonts, amssymb, graphicx, geometry, setspace
- **Page Layout**: 1.5cm margins, 0.9 line spacing for compactness
- **Math Mode**: Display equations `\[ \]`, inline math `$ $`

### VSCode Integration
- **Extension**: LaTeX Workshop
- **Auto-build**: Enabled on file save
- **Auto-clean**: Removes auxiliary files after build
- **PDF Viewer**: Integrated tab viewer

## 📝 Usage Patterns

### Creating New Notes
1. Copy `template.tex` to `YYYY-MM-DD/YYYY-MM-DD-notes.tex`
2. Update title: `[Course Code] Notes - [Topic/Date]`
3. Replace placeholder content with lecture material
4. Build with pdflatex or use VSCode auto-build

### Content Structure
- **Definitions**: Use `\textbf{Term:}` followed by explanation
- **Mathematical Formulas**: Display mode for key equations
- **Algorithms**: Numbered enumerate environment
- **Key Insights**: Bold formatting for important points
- **Examples**: Step-by-step calculations with intermediate steps

### Common LaTeX Patterns
```latex
% Key definitions
\textbf{Definition:} Explanation here

% Mathematical formulas
\[
\text{Formula} = \sum_{i=1}^{n} x_i
\]

% Algorithms
\begin{enumerate}
    \item Step 1: Initialize...
    \item Step 2: While condition...
    \item Step 3: Return result
\end{enumerate}

% Including images
\begin{figure}[h]
\centering
\includegraphics[width=0.8\textwidth]{image-name.png}
\caption{Description}
\end{figure}
```

## 🎓 Academic Contexts
This template works well for various subjects:
- **Mathematics**: Proofs, theorems, problem solutions
- **Computer Science**: Algorithms, data structures, complexity analysis
- **Physics**: Equations, derivations, experimental procedures
- **Engineering**: Technical specifications, design processes
- **Economics**: Models, formulas, statistical analysis

## 🤖 AI Assistant Guidelines

### When helping with this project:
1. **LaTeX Focus**: Prioritize LaTeX syntax and mathematical formatting
2. **Subject Agnostic**: Adapt to any academic discipline
3. **Template Consistency**: Maintain the established structure and style
4. **Compact Layout**: Favor dense, information-rich formatting
5. **Mathematical Precision**: Ensure correct mathematical notation
6. **Build Process**: Always test compilation after changes

### Common Tasks:
- Converting handwritten/text notes to structured LaTeX
- Adding mathematical formulas and algorithms
- Including and formatting diagrams/images
- Organizing content into logical sections
- Optimizing layout for readability and compactness

### File Organization:
- Each lecture/topic gets its own dated folder
- Images and diagrams in subfolder
- Maintain consistent naming: `YYYY-MM-DD-notes.tex`
- Git workflow: commit after each completed lecture

## 🔄 Workflow Integration
- **Version Control**: Git with meaningful commit messages
- **Build System**: LaTeX Workshop with auto-compilation
- **PDF Generation**: Immediate feedback with integrated viewer
- **Template Updates**: Propagate improvements across all notes

This template is optimized for academic efficiency and AI-assisted note-taking across all subjects! 