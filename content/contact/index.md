---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        
      email: vpiazza@cio.mx
      phone: 204 477 441 4200
      address:
        street: Cda. Loma del Bosque 115
        city: León
        region: Guanajuato
        postcode: '37150'
        country: México
        country_code: MX
      coordinates:
        latitude: '21.154194772914632'
        longitude: '-101.70475741865903'
      directions: Enter Building H and take the stairs to Floor 1
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: envelope
          icon_pack: fas
          name: Send email
          link: 'mailto:vpiazza@cio.mx'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form disabled
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     captcha: false
    design:
      columns: '1'

  - block: markdown
    content:
      title: Directions
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.png
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
