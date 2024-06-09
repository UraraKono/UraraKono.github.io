---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: yokonaga-robot.jpeg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  # - block: projects
  #   content:
  #     title: Projects
  #     username: admin
    # design:
    #   columns: '1'
    #   view: compact
  - block: skills
    content:
      title: Skills 
      username: admin
  - block: languages
    content:
      title: Languages
      username: admin

# # Projects
# sections:
#   # A section to display blog posts
#   - block: collection
#     id: section-1
#     content:
#       title: Section 1
#       subtitle: A subtitle
#       text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
#       # Display content from the `content/post/` folder
#       filters:
#         folders:
#           - post
#     design:
#       # Choose how many columns the section has. Valid values: '1' or '2'.
#       columns: '1'
#       # Choose your content listing view - here we use the `showcase` view
#       view: compact
#       # For the Showcase view, do you want to flip alternate rows?
#       flip_alt_rows: true
---
