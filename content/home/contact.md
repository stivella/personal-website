---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Contact
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  #form:
   # provider: netlify
    #formspree:
     # id:
    #netlify:
      # Enable CAPTCHA challenge to reduce spam?
     # captcha: false

  # Contact details (edit or remove options as required)
  #email: enrico.stivella@phd.unibocconi.it
  #email: enrico.stivella@unibocconi.it
  #email: stivella@uchicago.edu
  #phone: 888 888 88 88
  address:
    street: 5757 S. University Ave
    city: Chicago
    region: IL
    postcode: '60637'
    country: United States
    country_code: US
  coordinates:
    latitude: '41.789205983643'
    longitude: '-87.622382190515'
  directions: Kenneth C. Griffin Department of Economics, University of Chicago
  #office_hours:
  #  - 'Wednesday 15:00 to 16:30'
  # - 'Thursday 16:30 to 18:00'
  #appointment_url: ''  #inserire qui l'agenda virtuale bocconi
  contact_links:
    - icon: envelope
      icon_pack: fas
      name: stivella@uchicago.edu
      link: 'mailto:stivella@uchicago.edu'
    - icon: envelope
      icon_pack: fas
      name: For Bocconi students: enrico.stivella@unibocconi.it
      link: 'mailto:enrico.stivella@unibocconi.it'
design:
  columns: '2'
---
