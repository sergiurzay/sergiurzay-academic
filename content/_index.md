---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      username: admin

  - block: collection
    id: publications
    content:
      title: Selected Publications
      subtitle: ''
      text: ''
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: citation
      columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Use this form, or the information below, to contact me.
      email: sourzay@uic.es
      appointment_url: 'mailto:sourzay@uic.es?subject=Meeting%20request'
      office_hours:
        - 'By appointment'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/sergiurzay'
      autolink: true
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          captcha: false
    design:
      columns: '2'
---
