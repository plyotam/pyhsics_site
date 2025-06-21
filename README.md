# Interactive Physics Simulations

A bilingual (English/Hebrew) website featuring interactive physics simulations for students preparing for verbal exams.

## Features

- Bilingual support (English/Hebrew) with RTL layout for Hebrew
- Responsive design that works on all devices
- Dark mode support
- Interactive physics simulations

## Deployment

### GitHub Pages

1. Create a new repository named `yourusername.github.io` on GitHub
2. Push your code to the `main` branch
3. Go to Settings > Pages
4. Under "Source", select "Deploy from a branch"
5. Choose `main` branch and `/ (root)` folder
6. Click "Save"

Your site will be live at `https://yourusername.github.io`

### Local Development

Simply open `homepage.html` in your browser to run the site locally.

## Adding New Content

1. Add new HTML files for each simulation in the root directory
2. Update `homepage.html` with new cards for each simulation
3. Make sure to include both English and Hebrew versions of all text
4. Use the `en-content` and `he-content` classes for language-specific content

## Language Support

- The site automatically detects the user's browser language
- Users can manually switch between English and Hebrew using the language switcher in the top-right corner
- Language preference is saved in local storage

## License

This project is open source and available under the [MIT License](LICENSE).
