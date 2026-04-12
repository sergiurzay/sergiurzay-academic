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
      text: ''
      email: sourzay@uic.es
      office_hours:
        - 'By appointment'
      autolink: true
    design:
      columns: '2'
---
