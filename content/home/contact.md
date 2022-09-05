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
  email: eshorer1@jh.edu
  phone: +1 667 351 6062
  address:
    city: Baltimore
    region: MD
    postcode: '21231'
    country: United States
    country_code: US


design:
  columns: '2'
---
