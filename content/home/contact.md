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
      captcha: true

  # Contact details (edit or remove options as required)
  email: oaa9@njit.edu
  phone: 973 596 3000
  address:
    street: 218 Central Ave.
    city: Newark
    region: NJ
    postcode: '07102'
    country: United States
    country_code: US
  coordinates:
    latitude: '40.74456'
    longitude: '-74.17956'
  directions: Enter William S. Guttenberg Information Technologies Center (GITC) and take elevator to fourth floor.
  office_hours:
  appointment_url:
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: https://twitter.com/OliverAlvaRod

design:
  columns: '2'
---
