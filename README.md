# Pavel Sarwar Website

Modern, responsive, PWA-ready personal website for pavelsarwar.com.

## Pages
- Home
- About
- Media
- Contact
- Blog links to Local Guides Connect

## cPanel deployment
1. In cPanel > Git Version Control, clone this repository.
2. Edit `.cpanel.yml` and replace `CPANEL_USERNAME` with the actual cPanel username, or adjust `DEPLOYPATH` to the domain document root.
3. In cPanel Git Version Control, use **Update from Remote** and then **Deploy HEAD Commit**.

The site is static HTML/CSS/JS and does not require Node.js or a build step.
