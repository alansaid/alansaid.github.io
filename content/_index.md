---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: alan
      title: What makes a good recommender system?
      subtitle: Recommender systems and personalization
      primary_social: [envelope, google-scholar, github, linkedin]
      links:
        - name: Research
          url: /research/
        - name: Publications
          url: /publications/
        - name: Talks
          url: /talks/
  - block: recent-updates
    id: updates
    content:
      title: Recent updates
      items:
        - date: '2026-11-03'
          prefix: Talk
          ref: /talks/2026-11-03-gu-ai-for-science
        - date: '2026-09-15'
          prefix: Paper
          ref: /publications/2026-said-reproducibility
        - date: '2026-08-17'
          prefix: Paper
          ref: /publications/2026-silva-perceptions
    design:
      spacing:
        padding: ['2rem', '0', '2rem', '0']
  - block: contact
    id: contact
    content:
      title: Contact
      email: alansaid[at]acm.org
      phone: +46 766-18 20 26
      #appointment_url: 'https://calendly.com'
      address:
        street: Medicinaregatan 7b
        city: Gothenburg
        postcode: '41756'
        country: Sweden
        country_code: SE
      contact_links:
        - icon: map-location-dot
          icon_pack: fa
          name: 'Visiting address'
          link: 'https://maps.app.goo.gl/P1Li9jNZUKZCoJqT8'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
