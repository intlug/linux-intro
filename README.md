# An Introduction to Linux

A comprehensive presentation designed for INTLUG (Introduction to Linux User Group) covering the fundamentals of Linux for IT professionals and enthusiasts.

## About This Presentation

This presentation provides a structured introduction to Linux, covering:

- **Why Linux?** - Understanding the benefits of open source, freedom, control, stability, and security
- **Linux History & Philosophy** - From Unix origins to modern distributions, exploring the open-source movement
- **Core Concepts** - Filesystem Hierarchy Standard (FHS), permissions, processes, and package management
- **Desktop Environments** - Overview of GNOME, KDE, XFCE, and other popular environments
- **The Linux Ecosystem** - Major distributions (Ubuntu, Fedora, Debian, Arch) and their use cases
- **Command Line Basics** - Essential terminal commands and shell navigation
- **Career & Professional Development** - Why IT professionals need Linux knowledge, relevant job roles, and employer expectations
- **Community & Resources** - Getting involved with local LUGs, online forums, and learning resources

## Target Audience

- IT professionals looking to expand their Linux knowledge
- System administrators and DevOps engineers
- Students and career changers interested in Linux
- Anyone curious about open-source operating systems

## Building the Presentation

This presentation is built using [Marp](https://marp.app/), a Markdown-based presentation tool.

### Prerequisites

You'll need Node.js and npm installed on your system. Then install the Marp CLI:

```bash
npm install -g @marp-team/marp-cli
```

Or use it directly with npx (no installation needed):

```bash
npx @marp-team/marp-cli
```

### Generate HTML

To create an HTML file from the presentation:

```bash
npx @marp-team/marp-cli --html presentation.md -o presentation.html
```

Open `presentation.html` in your web browser to view the presentation.

### Generate PDF

To create a PDF version:

```bash
npx @marp-team/marp-cli --html presentation.md -o presentation.pdf
```

**Note:** PDF generation requires Chrome, Chromium, or Edge to be installed on your system.

### Generate PowerPoint (PPTX)

To create a PowerPoint presentation:

```bash
npx @marp-team/marp-cli presentation.md -o presentation.pptx
```

### Watch Mode for Development

For live preview while editing:

```bash
npx @marp-team/marp-cli -w presentation.md
```

This will watch for changes and automatically regenerate the output.

## Project Structure

```
linux-intro/
├── presentation.md          # Main presentation source
├── images/                  # Images and graphics
│   ├── intlug-banner.png   # INTLUG logo/banner
│   ├── fhs-diagram.svg     # Filesystem hierarchy diagram
│   ├── gnome-screenshot.png
│   └── linux-distros.jpg
├── README.md               # This file
├── LICENSE                 # GPLv3 license
└── .gitignore             # Git ignore rules
```

## Customization

The presentation uses the Gaia theme with custom styling including:
- Dracula-inspired color scheme
- Custom watermark and footer
- Two-column layouts for complex content
- 16:9 aspect ratio for modern displays

Edit `presentation.md` to customize content. The frontmatter section contains theme and styling configuration.

## License

This presentation is licensed under the GNU General Public License v3.0 (GPLv3). See the [LICENSE](LICENSE) file for details.

You are free to:
- Use this presentation for personal or commercial purposes
- Modify and adapt the content
- Share and distribute copies

Under the condition that any derivative works are also licensed under GPLv3.

## Contributing

Contributions are welcome! If you find errors or have suggestions for improvements:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## Acknowledgments

- INTLUG community for inspiration and feedback
- The Marp project for the excellent presentation framework
- The Linux community for decades of innovation

---

For more information about INTLUG or to get involved in your local Linux community, check the resources mentioned in the presentation!
