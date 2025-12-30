---
title: ''
date: 2025-12-30
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: ''
      username: admin
    design:
      background:
        color: white
      spacing:
        padding: ['60px', '0', '60px', '0']
  
  - block: collection
    id: featured
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        featured_only: true
      count: 3
    design:
      columns: '1'
      view: compact
      background:
        color: '#fafafa'
      spacing:
        padding: ['60px', '0', '60px', '0']
  
  - block: contact
    id: contact
    content:
      title: Contact
      email: camilo.nietomatiz@utsa.edu
      address:
        street: 'Department of Political Science & Geography, UTSA'
        city: San Antonio
        region: TX
        postcode: '78249'
        country: United States
        country_code: US
    design:
      columns: '2'
      spacing:
        padding: ['60px', '0', '60px', '0']
---
