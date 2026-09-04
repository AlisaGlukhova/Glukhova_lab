---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        We are located at the Walter and Eliza Hall Institute of Medical Research (WEHI), Melbourne, Australia
     email: glukhova.a@wehi.edu.au
     phone: ''
      address:
        street: 1G Royal Parade
        city: Parkville
        region: VIC
        postcode: '3052'
        country: Australia
        country_code: AU
      coordinates:
        latitude: '-37.7993'
        longitude: '144.9521'
      directions: 
      office_hours:
        - ''
      appointment_url: ''
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
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
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
