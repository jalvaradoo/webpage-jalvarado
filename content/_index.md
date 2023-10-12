---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

# Toggle between the various page layout types.
#   1 = List
#   2 = Compact
#   3 = Card
#   5 = Showcase

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: portfolio
    id: working_papers
    content:
      title: Working Papers
      filters: 
        folders:
          - working_papers
        featured_only: true
    design:
      columns: '1'
      view: showcase
      flip_alt_rows: false
  # - block: portfolio
  #  id: work_in_progress
  #  content:
  #    title: Work in Progress
  #    filters: 
  #      folders:
  #        - work_in_progress
  #      featured_only: true
  #  design:
  #    columns: '2'
  #    view: compact
  #    flip_alt_rows: false
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: twilner@u.northwestern.edu
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        street: 2211 Campus Dr
        city: Evanston
        region: IL
        postcode: '60208'
        country: United States
        country_code: US
     # office_hours:
     #   - 'Monday 10:00 to 13:00'
     #   - 'Wednesday 09:00 to 10:00'
     # contact_links:
     #   - icon: twitter
     #     icon_pack: fab
     #     name: DM Me
     #     link: 'https://twitter.com/Twitter'
     #   - icon: skype
     #     icon_pack: fab
     #     name: Skype Me
     #     link: 'skype:echo123?call'
     #   - icon: video
     #     icon_pack: fas
     #     name: Zoom Me
     #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
      #    # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    design:
      columns: '2'
 # - block: portfolio
 #   id: projects
 #   content:
 #     title: Projects
 #     filters:
 #       folders:
 #         - project
 #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
 #     default_button_index: 0
 #     # Filter toolbar (optional).
 #     # Add or remove as many filters (`filter_button` instances) as you like.
 #    # To show all items, set `tag` to "*".
 #     # To filter by a specific tag, set `tag` to an existing tag name.
 #     # To remove the toolbar, delete the entire `filter_button` block.
 #     buttons:
 #       - name: All
 #         tag: '*'
 #       - name: Deep Learning
 #         tag: Deep Learning
 #       - name: Other
 #         tag: Demo
 #   design:
 #     # Choose how many columns the section has. Valid values: '1' or '2'.
 #     columns: '1'
 #     view: showcase 
 #     # For Showcase view, flip alternate rows?
 #     flip_alt_rows: false
---
