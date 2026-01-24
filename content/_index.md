---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem' # Default section spacing

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: |-
        - Ο Ευάγγελος Αλεξίου είναι **Επιμελητής Α΄ Αγγειοχειρουργός** στο **Πανεπιστημιακό Γενικό Νοσοκομείο Ιωαννίνων**.
        - Διατηρεί **ιδιωτικό ιατρείο στο Αγρίνιο**.
        - Εξειδικεύεται στις **ελάχιστα επεμβατικές ενδαγγειακές τεχνικές** αλλά και στις **μείζονες ανοιχτές επεμβάσεις αρτηριών και φλεβών**.
        - Διαθέτει πλούσιο ερευνητικό και συγγραφικό έργο με **περισσότερες από 50 ξενόγλωσσες δημοσιεύσεις** και συντελεστή επιστημονικής απήχησης **h-index 20**.
        - Είναι **μέλος του Διοικητικού Συμβουλίου** και **ταμίας** της **Ελληνικής Εταιρείας Αγγειακής και Ενδαγγειακής Χειρουργικής**.
      button:
        text: Κλείστε ραντεβού
        url: '/#contact'
      headings:
        about: Επαγγελματικό προφίλ
        education: Πτυχία - Ειδικότητα
        interests: Ενδιαφέροντα
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium # small, medium (default), large, xl, xxl
        shape: circle # circle (default), square, rounded

  - block: markdown
    content:
      title: '🔬 Ερευνητικά Ενδιαφέροντα'
      subtitle: 'Κλινική έρευνα – Καινοτόμες τεχνικές'
      text: |-
        - Χρήση της τεχνητής νοημοσύνης στην Αγγειοχειρουργική
        - Φλεβικές παθήσεις
        - Νέες διαγνωστικές συσκευές
        - Σύνθετα ανευρύσματα αορτής
    design:
      columns: 1

  # ↓↓↓ Features block με τεράστια custom SVG εικονίδια
  - block: features
    content:
      title: '🥼 Χειρουργικές Επεμβάσεις'
      items:
        - icon: open-surgery
          icon_pack: custom
          name: 'Ανοικτή αορτική χειρουργική'
        - icon: evar
          icon_pack: custom
          name: 'Ενδαγγειακή αποκατάσταση ανευρυσμάτων EVAR / TEVAR'
        - icon: stenosis
          icon_pack: custom
          name: 'Καρωτιδική ενδαρτηρεκτομή'
        - icon: graft
          icon_pack: custom
          name: 'Μηρο-ιγνυακή και περιφερική παράκαμψη'
        - icon: dialysis
          icon_pack: custom
          name: 'Μοσχεύματα / Φίστουλες αιμοκάθαρσης'
        - icon: stent
          icon_pack: custom
          name: 'Αγγειοπλαστική αρτηριών'
        - icon: evla
          icon_pack: custom
          name: 'Laser κιρσών'
    design:
      columns: 3

  - block: collection
    id: news
    content:
      title: '📚 Πρόσφατες Δημοσιεύσεις'
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: '📑 Ομιλίες & Συνέδρια'
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: blog
    content:
      title: '🎬 Blog / Βίντεο'
      subtitle: ''
      text: ''
      page_type: blog # Page type to display. E.g. post, talk, publication...
      count: 5 # Number of pages to show (0 = all)
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0 # Skip this many pages
      order: desc # Page order: descending (desc) or ascending (asc) date.
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]

  - block: markdown
    id: contact
    content:
      title: '📞 Επικοινωνία'
      text: |-
        - 📧 **Email:** [v.alexiou@aibs.gr](mailto:v.alexiou@aibs.gr)
        - 📱 **Κινητό:** [+30 699 3031 175](tel:+306993031175)
        - ☎️ **Γραφείο ΠΓΝ Ιωαννίνων:** [+30 26510 99694](tel:+302651099694)
        - 🏥 **[Ιατρείο Αγρινίου – Google Maps](https://maps.app.goo.gl/XTBTAhAXWQJPyz7c9)**
        - 🧬 **ORCID:** [0000-0003-1388-4880](https://orcid.org/0000-0003-1388-4880)
        - 📊 **Scopus:** [18433424100](https://www.scopus.com/authid/detail.uri?authorId=18433424100)
        - 🩺 **ΕΕΑΕΧ:** [Προφίλ](https://www.vascularsociety.gr/user/vanalex)
        - 💼 **LinkedIn:** [Profile](https://gr.linkedin.com/in/vangelis-alexiou-27b9a432)
    design:
      columns: 1
---
