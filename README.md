# tongkyu.kim.github.io
Personal CV website for Tongkyu Kim

## Local Development

Start the local development server:
```bash
npm start
# or
python3 -m http.server 8000
```

Then open your browser to: http://localhost:8000

## File Structure

```
/
├── index.html          # Main website file
├── profile.jpg         # Profile photo (add this file)
├── package.json        # NPM configuration
├── README.md          # This file
└── .gitignore         # Git ignore rules
```

## Development Commands

- `npm start` or `npm run serve` - Start local development server
- `npm run dev` - Start development server (same as above)
- `npm run build` - No build step needed for static site
- `npm run deploy` - Reminder about GitHub Pages deployment

## Adding Your Profile Photo

Add a profile photo named `profile.jpg` to the root directory. The recommended size is 300x300 pixels or larger, square aspect ratio.

## Deployment

This website automatically deploys to GitHub Pages when you push to the main branch at:
https://donkee96.github.io/tongkyu.kim.github.io

## Customization

Edit the `index.html` file to:
- Update your personal information
- Add your actual positions and publications
- Update social media links
- Modify the styling in the `<style>` section
