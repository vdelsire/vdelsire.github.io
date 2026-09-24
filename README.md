# Victor Delaney Sire — portfolio

A responsive, dark portfolio built with HTML, CSS, and JavaScript. No build step or package installation is required.

## Preview

Open `index.html` in your browser, or run this command from the project directory and visit http://localhost:8000:

```sh
python3 -m http.server 8000
```

## Update projects and experiences

Edit `content.js`. Each project and experience has a `media` array. Put your files in the `media/` folder, then add entries like:

```js
media: [
  { type: 'image', src: 'media/linkage-assembly.jpg', alt: 'Assembled linkage on its machined base', caption: 'Final mechanical assembly.' },
  { type: 'video', src: 'media/linkage-demo.mp4', poster: 'media/linkage-poster.jpg', caption: 'Motion-control demonstration.' }
]
```

Use MP4 videos for broad browser support. Captions, poster images, and cover images are optional. Add a `cover: 'media/project-photo.jpg'` property to a project to replace its concept illustration on the home page. Galleries appear inside the project details or expanded experience. These are file-based edits; the site does not include an upload dashboard or backend.

Edit `about.html` for biography, education, and skills. Edit `index.html` for the introduction and contact text. Replace `Victor_Delaney_Sire_Resume.pdf` to update the downloadable résumé. The current content is based on the supplied résumé; the illustrations are conceptual drawings, not actual project photographs or CAD models.

## Publish

Upload this folder to any static website host, keeping the PDF, `assets/`, and `media/` paths intact. Google Fonts are optional; system fonts serve as fallbacks when offline. Contact links open an email client.
