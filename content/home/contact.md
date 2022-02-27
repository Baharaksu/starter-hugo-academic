---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true
  
  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

  # Contact details (edit or remove options as required)
  email: b.aksu@lancaster.ac.uk
  
  address:
    street: Lancaster University
    city: Lancaster
    region: Lancashire
    postcode: 'LA1 4YV'
    country: United Kingdom

  office_hours:
    - ''
    - ''

  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter/baharaxu'


design:
  columns: '2'
---
