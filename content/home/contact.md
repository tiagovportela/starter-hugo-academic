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
  email: tiagovportela[at]protonmail.com
  phone:
  address:
    street: Rua Oliveira Monteiro 351
    city: Porto
    region:
    postcode: "94305"
    country: Portugal
    country_code: PT
  coordinates:
    latitude:
    longitude:
  directions:
  office_hours:
    - "Week Day 10:00 to 19:00"

  appointment_url: "https://calendly.com"
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: "https://twitter.com/tiago_v_p_"
    # - icon: video
    #   icon_pack: fas
    #   name: Zoom Me
    #   link: 'https://zoom.com'

design:
  columns: "2"
---
