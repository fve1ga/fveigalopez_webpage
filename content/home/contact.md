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
  email: fveiga@ing.uc3m.es
  phone: 0034-669682186
  address:
    street: Avenida de la Universidad 30
    city: Leganés
    region: Madrid
    postcode: '28912'
    country: Spain
    country_code: ES
  coordinates:
    latitude: '40.18'
    longitude: '3.43'
  directions: Enter Building 1 and take the stairs to Office 1.1.D22 on Floor 1
  office_hours:
    - 'Monday 10:00 to 13:00'
    - 'Wednesday 09:00 to 10:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/FerrVeiga'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
