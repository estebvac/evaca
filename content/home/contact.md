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
  email: estebvac@gmail.com
  phone: +49 2461 61 85047
  address:
    street: Wilhelm-Johnen-Straße
    city: Jülich
    region: Nordrhein-Westfalen
    postcode: '52428'
    country: Germany
    country_code: DE
  coordinates:
    latitude: '50.90299638'
    longitude: '6.4071650'
  directions: Institute of Neuroscience and Medicine INM-1
  office_hours:
    - 'Mo-Fr 08:00 to 17:00'
  appointment_url: 'https://calendly.com'
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
