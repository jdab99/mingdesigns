Portfolio project images go here.

TODO(client): drop one cover image per project, named by its `id` in
src/data/projects.ts, e.g.:

  meridian-coffee.jpg
  atlas-review.jpg
  field-notes-botanica.jpg
  verso-studio.jpg
  nocturne-festival.jpg
  harbor-press.jpg
  grove-skincare.jpg
  signal-conference.jpg

Recommended: ~1600px on the long edge, JPG/WebP, optimized.
Until an image exists, the site shows a clearly-marked greyscale placeholder.
Also set each project's `cover` (and gallery `src`) in src/data/projects.ts,
and flip the PlaceholderImage `src` in WorkTile/ProjectModal to use it.
