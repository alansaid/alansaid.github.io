---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: alan
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: contact
    id: contact
    content:
      title: Contact
      email: alansaid[at]acm.org
      phone: +46 766-18 20 26
      #appointment_url: 'https://calendly.com'
      address:
        street: Forskningsgången 6
        city: Gothenburg
        postcode: '41756'
        country: Sweden
        country_code: SE
      contact_links:
        - icon: map-location-dot
          icon_pack: fa
          name: 'Visiting address'
          link: 'https://maps.app.goo.gl/DZB87JQUWRvBWGqF7'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
