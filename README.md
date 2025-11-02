# odin-recipes
## Description
This is a web development project for creating a simple recipe website.

## What skills you will have/ have demonstrated once you have completed it?
- Interconnect multiple web pages and home page.
- Collect image from various sources for the recipe.
- Information gather: How to gather recipe info from the internet, compare them and select the one which is less complex and easy to understand for the Users.
- Sort Ingredients in Unordered list and Steps in Ordered list.
- Inspect a website and find the src link of an image for an website. From there find the actual dimension of image.
- Specified actual image size (width, height) for every image. This is to prevent content jumping as images load.
- Figured out, out of 6 heading tags, which heading tag to use to create a more appealing website for a better UX.
- Understood when to use rel="noopener noreferrer". It's safe to not use rel="noopener noreferrer" to href to my own created web pages since it's secure. Must use rel="noopener noreferrer" to href External Links.
- Use wget command to download images from a source url. 
- Use sip -g pixelWidth -g pixelHeight filename.jpg command to Check image dimension (width, height) from the zsh for the downloaded images.
- Save space by rm the downloaded images; Instead added source link in img tag.

### Project structure
.
├── README.md
├── index.html
└── recipes
    ├── afghani-kabuli-pulao.html
    ├── ilish-bhaja.html
    └── shorshe-ilish.html