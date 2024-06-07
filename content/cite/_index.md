---
title: My page
type: landing

design:
  # Section spacing
  spacing: '2rem'

sections:
  - block: markdown
    content:
      title: Main FEniCSx citations
      text: |
        If you use FEniCS in your research, the developers would be grateful if you would cite the relevant publications.

        If your code starts with import dolfinx, you are using FEniCSx and should cite the papers on this page. FEniCSx is organized as a collection of components, so to give proper credit, please cite the indicated references for each relevant component. You can find this list of papers in BibTeX format here.

  - block: collection
    content:
      title: Main FEniCSx citations
      text: |
        If you use FEniCS in your research, the developers would be grateful if you would cite the relevant publications.

        If your code starts with `import dolfinx`, you are using FEniCSx and should cite the papers on this page. FEniCSx is organized as a collection of components, so to give proper credit, please cite the indicated references for each relevant component. You can find this list of papers in BibTeX format here.
      filters:
        folders:
          - publication
        exclude_featured: false
        tags: ['dolfinx', 'basix', 'ufl']
      design:
        view: citation
        spacing:
            # Customize the section spacing. Order is top, right, bottom, left.
            padding: ['10px', '0', '0px', '0']
    design:
      view: article-grid
      fill_image: false
      columns: 3

  - block: collection
    content:
      title: DOLFINx
      text: Something about DOLFINx.
      filters:
        folders:
          - publication
        exclude_featured: false
        tag: dolfinx
    design:
      view: citation

  - block: collection
    content:
      title: Basix
      text: Say something about Basix.
      filters:
        folders:
          - publication
        exclude_featured: false
        tag: basix
    design:
      view: citation

  - block: collection
    content:
      title: UFL
      filters:
        folders:
          - publication
        # exclude_featured: false
        tag: basix
    design:
      view: citation

# - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: 'Check out my recent blog posts below!'
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       # The folders to display content from
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       publication_type: ""
  #       featured_only: false
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #     # Choose how many pages you would like to offset by
  #     # Useful if you wish to show the first item in the Featured widget
  #     offset: 0
  #     # Field to sort by, such as Date or Title
  #     sort_by: 'Date'
  #     sort_ascending: false
  #   design:
  #     # Choose a listing view
  #     view: card
---

