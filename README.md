# Workshop

A monorepo containing various personal projects and experiments.

## Overview

This repository serves as a collection of web-based applications, tools, and experimental projects. Each project is self-contained within its own directory under `projects/`.

## Structure

```
workshop/
├── index.html              # Landing page with links to all projects
├── projects/
│   ├── flight-sim/         # Google Flight Simulator
│   ├── json-parser/        # JSON Parser Online
│   ├── solar-system/       # Solar System Visualization
│   └── format-converter/   # Format Converter Tool
└── README.md
```

## Projects

Each project lives in its own directory under `projects/` and can be accessed via:
- Locally: `file:///path/to/workshop/projects/<project-name>/index.html`
- GitHub Pages: `username.github.io/workshop/projects/<project-name>/`

## Adding New Projects

1. Create a new directory under `projects/`
2. Add your project files (at minimum an `index.html`)
3. Update the main `index.html` to include a link to your new project
4. Update this README with project information

## GitHub Pages Setup

1. Push this repository to GitHub
2. Go to repository Settings → Pages
3. Select "Deploy from a branch"
4. Choose `main` branch and `/ (root)` folder
5. Save and wait for deployment
6. Access at: `https://username.github.io/workshop/`

## Local Development

Simply open `index.html` in your browser to view the landing page and navigate to individual projects.

## License

Individual projects may have their own licenses. Please check each project directory for specific licensing information.
