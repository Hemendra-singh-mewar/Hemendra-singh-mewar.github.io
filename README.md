# Hemendra Singh Mewar | Academic website

A responsive academic profile focused on cryogenic silicon, mechanical loss and optical thermometry.

## Publish on GitHub Pages

In repository Settings → Pages, select **Deploy from a branch**, choose **main** and **/ (root)**, then save.

The intended address is https://hemendra-singh-mewar.github.io/.

## Editing

- `index.html`: biography, research, projects and profile links.
- `styles.css`: colours and responsive layout.
- `talks.json`: presentation entries, displayed automatically on the website.
- `presentations/`: slides, images and presentation notes.
- `.github/ISSUE_TEMPLATE/presentation.yml`: public intake form.

To add a talk, add an object to the JSON array with title, date, event, location and summary. Optional fields: slides, image, imageAlt and url. Use relative file paths or HTTPS URLs. Example format:

```json
[
  {
    "title": "Your presentation title",
    "date": "YYYY-MM-DD",
    "event": "Conference name",
    "location": "City, country",
    "summary": "A brief account of your presentation.",
    "slides": "presentations/example/slides.pdf",
    "image": "presentations/example/photo.jpg",
    "imageAlt": "A descriptive caption"
  }
]
```

Replace example values with actual material before publishing. The website currently uses initials in place of a portrait. No publication counts are estimated and no conference attendance is inferred.

Submitting an issue does not automatically create an entry or publish to external platforms.
