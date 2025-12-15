# l2n.me

My personal website built with Hugo, featuring my about page, projects, and links to my content across the web.

**Live Site**: [https://l2n.me](https://l2n.me)

## About

This is my personal web space where I share information about myself, my work, and my projects. The site includes:

- **About**: Background, professional experience, and interests
- **Links**: Collection of my digital projects and content (YouTube, CV, slides, and other projects)

## Tech Stack

- **Static Site Generator**: [Hugo](https://gohugo.io/)
- **Theme**: [gruvhugo](https://gitlab.com/avron/gruvhugo)
- **Hosting**: GitHub Pages

## Development

### Prerequisites

- [Hugo Extended](https://gohugo.io/installation/) (v0.128.0 or later)
- Git

### Setup

1. Clone the repository:
```bash
git clone https://github.com/luanguimaraesla/l2n.me.git
cd l2n.me
```

2. Initialize theme submodule:
```bash
git submodule update --init --recursive
```

3. Run the development server:
```bash
hugo server
```

The site will be available at `http://localhost:1313/`

### Building

To build the static site for production:

```bash
hugo
```

Static files will be generated in the `docs/` directory, which is configured for GitHub Pages deployment.

## Project Structure

```
.
├── content/
│   ├── about/          # About page content
│   └── links/          # Links page content
├── static/             # Static assets (images, CSS, etc.)
├── themes/
│   └── gruvhugo/       # Theme (git submodule)
├── config.toml         # Hugo configuration
└── docs/               # Generated static site (published to GitHub Pages)
```

## Configuration

Key configuration is in `config.toml`:
- Site metadata and title
- Menu structure
- Social links
- Theme customization

## License

Content is my own. Theme is licensed under its respective license.

## Contact

Feel free to reach out at [luan@l2n.me](mailto:luan@l2n.me)
