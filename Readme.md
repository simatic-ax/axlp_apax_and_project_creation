# Get started with Apax and AX Projects

## Purpose
This repository provides a learning path for getting started with Apax and AX Projects. It includes a presentation that covers the basics of package management, using Apax, building projects, and more.

## Summary of slides.md
The `slides.md` file contains the content for the presentation. To view the presentation locally, use the command:
```
reveal-md slides.md --watch --theme simatic-ax.css -css simatic-ax.css
```
To generate a static version of the presentation for GitHub Pages, use the command:
```
reveal-md slides.md --static docs --theme simatic-ax.css -css simatic-ax.css --assets-dir dist --staticDirs img
```
The static files will be generated in the `docs` directory, which can be used to host the presentation on GitHub Pages.

# How to Contribute
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes to the `slides.md` file or other relevant files.
4. Commit your changes and push the branch to your fork.
5. Create a pull request with a description of your changes.
