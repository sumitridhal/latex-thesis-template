# LaTeX Thesis Template

A clean, professional LaTeX template for academic theses and dissertations.

## Features

- **Clean Structure**: Minimal, focused template with essential components
- **Two Chapters**: Template includes Introduction and Literature Review chapters
- **Example Content**: Placeholder text and examples to guide your writing
- **Professional Formatting**: Proper margins, spacing, and typography
- **Bibliography Support**: BibLaTeX integration with example citations
- **Figure Examples**: Sample figures to demonstrate proper usage

## File Structure

```
LaTeX-Thesis-Template/
├── main.tex                 # Main document file
├── reference.bib            # Bibliography database
├── logo.png                 # University/Institution logo
├── chapters/
│   ├── 1/
│   │   └── 1.tex          # Chapter 1: Introduction
│   └── 2/
│       ├── 2.tex          # Chapter 2: Literature Review
│       └── figures/       # Chapter figures
└── README.md               # This file
```

## Getting Started

### 1. Customize Personal Information
Edit `main.tex` and replace the placeholder text:
- `[Your Thesis Title Here]`
- `[Your Degree]`
- `[Your Full Name]`
- `[Your Student ID]`
- `[Your Supervisor's Name]`
- `[Your Department Name]`
- `[Your University Name]`
- `[Month, Year]`

### 2. Write Your Abstract
Replace the placeholder text in the abstract section with your actual research summary.

### 3. Customize Chapters
- **Chapter 1**: Modify the introduction sections to match your research
- **Chapter 2**: Update the literature review with your field-specific content
- **Add More Chapters**: Copy the chapter structure and add your content

### 4. Add Your References
- Replace example citations in `reference.bib` with your actual sources
- Use the provided format as a template for new entries

### 5. Add Your Figures
- Place figures in the appropriate chapter's `figures/` directory
- Reference them in your text using `\includegraphics` and `\ref`

## Compilation

### Prerequisites
- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- BibLaTeX backend (Biber)

### Build Commands
```bash
# First compilation
pdflatex main.tex

# Generate bibliography
biber main

# Second compilation (for references)
pdflatex main.tex

# Third compilation (for final formatting)
pdflatex main.tex
```

Or use your preferred LaTeX editor's build system.

## Customization

### Adding New Chapters
1. Create a new directory: `chapters/X/`
2. Create `X.tex` file with chapter content
3. Add `\input{chapters/X/X}` to `main.tex`

### Modifying Styles
- Edit package configurations in the preamble
- Modify theorem environments as needed
- Adjust page geometry in the `\geometry` command

### Adding Packages
Include additional packages in the preamble as needed for your research.

## Example Usage

The template includes:
- **Citations**: Example references showing proper BibLaTeX usage
- **Figures**: Sample figure inclusion with captions and labels
- **Sections**: Structured content with proper hierarchy
- **Mathematics**: Mathematical environments and commands

## Tips

1. **Keep it Clean**: Don't add unnecessary packages unless required
2. **Consistent Naming**: Use consistent file naming conventions
3. **Regular Backups**: Keep regular backups of your work
4. **Version Control**: Consider using Git for version control
5. **Test Compilation**: Test compilation regularly as you add content

## Support

This template provides a solid foundation for academic writing. Customize it according to your institution's requirements and personal preferences.

## License

This template is provided as-is for academic use. Modify and distribute as needed.
