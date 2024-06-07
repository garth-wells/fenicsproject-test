---
title: "Construction of arbitrary order finite element degree-of-freedom maps on polygonal and polyhedral cell meshes"
authors:
- Matthew W. Scroggs
- Jørgen S. Dokken
- Chris N. Richardson
- Garth N. Wells

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-09-01T00:00:00Z"
doi: "10.1145/3524456"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "ACM Transactions on Mathematical Software"
publication_short: ""

abstract: We develop a method for generating degree-of-freedom maps for arbitrary order Ciarlet-type finite element spaces for any cell shape. The approach is based on the composition of permutations and transformations by cell sub-entity. Current approaches to generating degree-of-freedom maps for arbitrary order problems typically rely on a consistent orientation of cell entities that permits the definition of a common local coordinate system on shared edges and faces. However, while orientation of a mesh is straightforward for simplex cells and is a local operation, it is not a strictly local operation for quadrilateral cells and, in the case of hexahedral cells, not all meshes are orientable. The permutation and transformation approach is developed for a range of element types, including arbitrary degree Lagrange, serendipity, and divergence- and curl-conforming elements, and for a range of cell shapes. The approach is local and can be applied to cells of any shape, including general polytopes and meshes with mixed cell types. A number of examples are presented and the developed approach has been implemented in open-source libraries.

tags:
  - basix
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://zenodo.org/records/10447666
url_code: https://github.com/fenics/basix
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---