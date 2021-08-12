# Print-to-PDF HTML Resume Template

> A Stand-Out, easy-to-edit, classy resume template that's perfect for your website, blog, and job-application PDF uploads.

[![](/examples/john-doe-resume-preview.png)](/examples/john-doe-resume.png)

## Features

- [x] Sleek, Professional, Classy
- [x] Vanilla HTML & CSS
- [x] Print-to-PDF
- [x] Renders properly in "Evergreen" browsers since 2016
- [x] Copy, Paste, Customize

## Examples

- [AJ ONeal (html)](https://coolaj86.com/resume/)
- [John Shaver (html)](https://jshaver.net/resume/)
- [Min-Zhong "John" Lu (pdf)](https://mnjul.net/cv/resume.pdf)

## Make Your Own

1. <kbd><a href="https://github.com/BeyondCodeBootcamp/html-resume/generate">Use this template</a></kbd> (from the [Beyond Code Resume repo](https://github.com/BeyondCodeBootcamp/html-resume))
2. Use [git](https://webinstall.dev/git/) to download this project (or get the [zip](https://github.com/BeyondCodeBootcamp/html-resume/archive/refs/heads/main.zip) and find the dependencies)
   ```bash
   git clone --recursive --shallow-submodules --depth=1 https://github.com/BeyondCodeBootcamp/html-resume.git
   ```
3. Preview `html-resume/` in your browser
   - macOS: `open html-resume/index.html`
   - Linux: `xdg-open html-resume/index.html`
   - Windows 10: `start html-resume/index.html`
4. Copy this `html-resume/` to your web server as `/resume/`
   - (i.e. your resume should be viewable at https://YOUR-SITE.com/resume/)

Use [VS Code](https://code.visualstudio.com) [+ Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
or [vim + Prettier](https://webinstall.dev/vim-essential)
to edit `index.html` and `style.css` and season to taste.

For reference, this is how I would clone this repository so that I can `git push` to it:

```bash
git clone ssh://git@github.com/BeyondCodeBootcamp/html-resume.git
pushd html-resume/
git submodule init
git submodule update --recursive --depth=1
```

I show the other example above because it's just one line, but you won't be able to `git commit` and `git push` changes.

# Tips

- Printable as US Letter in Portrait mode
  - (PR for A4 support welcome)
- Brave, Google Chrome, and Edge
  - Set **Margin** to **None**
  - Print **Background Graphics**
  - Don't print headers and footers
  - Save as PDF
- Firefox:
  - You may eed to remove page margins in **about:config**
  - Uncheck **Ignore Scaling and Shrink To Fit Page Width**
  - Check **Print Background Colors**
  - Clear out the headers and footers
  - Save as PDF

# Acknowledgements

- [Inspired](https://blogs.purincess.tw/matrixblog/2016/04/typesetting-resume-with-html-and-css/) [by](https://github.com/mnjul/html-resume) Paolo Zupin and [Shih-Wen "Angela" Chen](https://angelachen.design/2014/resume.pdf)
- Created as a Print-to-PDF HTML document by [Min-Zhong "John" Lu](https://mnjul.net/cv/resume.pdf)
- Modified by [AJ ONeal](https://coolaj86.com/resume/)
- This fork maintained as part of Beyond Code Bootcamp

## Dependencies

- **Fonts** (free Google Fonts)
  - [Open Sans](https://www.google.com/fonts/specimen/Open+Sans)
  - [Source Code Pro](https://fonts.google.com/specimen/Source+Code+Pro)
  - [Source Sans Pro](https://www.google.com/fonts/specimen/Source+Sans+Pro)
- **Icons**
  - [Font Awesome](https://fortawesome.github.io/Font-Awesome/)
- **CSS**
  - [Normalize.css](https://necolas.github.io/normalize.css/)

# License

Apache-2.0

See [LICENSE](/LICENSE).
