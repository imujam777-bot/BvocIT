# BVOC IT Hub — GTU B.Voc IT Semester 3

A beginner-friendly static website starter built with HTML, CSS and JavaScript.

## Pages
- `index.html` — homepage
- `subjects.html` — syllabus subjects and units; click Advanced Java to open its resource page
- `advanced-java.html` — all Advanced Java notes, handwritten unit sheets and past papers in one place
- `diagrams.html` — searchable diagram library
- `questions.html` — important Q&A library
- `papers.html` — previous-year paper library
- `practicals.html` — practicals and viva library

## Run locally
1. Extract this folder.
2. Open it in Visual Studio Code.
3. Open `index.html` in a browser, or use the Live Server extension.

## Add resources
1. Put your PDF or image in the appropriate folder under `resources/`.
2. Open `js/resources.js`.
3. Add or edit an object in the `resources` array.
4. Set `subjectCode` to one of the four subject codes.
5. Set `type` to `diagram`, `questions`, `paper`, or `practical`.
6. Set `file` to the relative path, for example `resources/diagrams/cpu-block-diagram.png`.

Example:
```js
{
  id: 7,
  title: "CPU Block Diagram",
  subjectCode: "1130504",
  type: "diagram",
  unit: "Unit II",
  description: "Labeled CPU block diagram",
  file: "resources/diagrams/cpu-block-diagram.png",
  priority: "Revision"
}
```

## Important notes
- Advanced Java study notes PDF is included at `resources/advanced-java/Advanced_Java_BVOC_IT_Hub_Study_Notes.pdf`; it contains concise explanations, revision points, practice questions and diagram guides for Units I–IV.
- Advanced Java past papers currently included: Summer 2026, Winter 2025, Summer 2025, Winter 2024 and Winter 2023. Other sample resource entries are placeholders, not official GTU questions or actual past papers.
- The subject codes and the visible syllabus units are organized from the syllabus documents shared for this project. Review unit headings against the originals before publishing.
- This version has no database, login or upload form. Changes to files and `resources.js` require republishing the site.
- Anyone can view published files. Do not upload private class information or copyrighted material unless you have permission.
- Google Fonts needs an internet connection; system fonts will still work if it is unavailable.

## Publishing
You can publish the folder with a static hosting provider such as GitHub Pages or Netlify. Upload the folder contents while preserving the folder structure.

## Subject-first navigation
- Students choose **Advanced Java** from the Subjects page or homepage to open `advanced-java.html`.
- Study notes PDF, all four handwritten unit sheets and five past papers are grouped inside that subject page.
- Main navigation is simplified to Home and Subjects so resources are not presented as separate top-level sections.


Branding update: the B.VOC IT Students of JVIMS emblem is used as the site logo and browser favicon.
