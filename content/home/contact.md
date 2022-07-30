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
  email: abahl@eoas.ubc.ca
  address:
    department: Earth, Oceanic and Atmospheric Sciences Department
    instituion: The University of British Columbia 
    city: Vancouver
    region: BC
    postcode: 'V6T 1Z4'
    country: Canada
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: '[https://twitter.com/BahlAlexis]'
    - icon: ResearchGate
      icon_pack: fas
      name: Read me
      link: '[https://www.researchgate.net/profile/Alexis-Bahl]'

design:
  columns: '2'
---
