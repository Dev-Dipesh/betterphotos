# BetterPhotos

### A simple website with css best practices and responsive web design

![BetterPhotos](betterphotos.png)

## Project Structure

1. **src** - Contains the source files
   - **main.scss** - The main SCSS file
   - **style.css** - The compiled CSS file created by the `compile` script for development
2. **build** - Contains the compiled and optimized files
   - **compiled.css** - The compiled CSS file
   - **prefixed.css** - The CSS file with vendor prefixes
   - **style.css** - The optimized CSS file
   - **index.html** - The HTML file

## Commands

1. **npm run compile** - Compiles the SCSS file to CSS for development with hot reloading
2. **npm run build:compile** - Compiles the SCSS file to CSS for production
3. **npm run build:prefixes** - Adds vendor prefixes to the CSS file
4. **npm run build:optimize** - Optimizes the CSS file
