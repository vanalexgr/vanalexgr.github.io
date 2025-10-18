---
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: |-
        - Ο Ευάγγελος Αλεξίου είναι **Επιμελητής Α΄ Αγγειοχειρουργός** και υπηρετεί από το 2019 στο **Πανεπιστημιακό Γενικό Νοσοκομείο Ιωαννίνων**.
        - Διατηρεί **ιδιωτικό ιατρείο στο Αγρίνιο**.
        - Εξειδικεύεται στις **ελάχιστα επεμβατικές ενδαγγειακές τεχνικές** αλλά και στις **μείζονες ανοιχτές επεμβάσεις αρτηριών και φλεβών**.
        - Διαθέτει πλούσιο ερευνητικό και συγγραφικό έργο με **περισσότερες από 50 ξενόγλωσσες δημοσιεύσεις** και συντελεστή επιστημονικής απήχησης **h-index 20**.
        - Είναι **μέλος του Διοικητικού Συμβουλίου** και **ταμίας** της **Ελληνικής Εταιρείας Αγγειακής και Ενδαγγειακής Χειρουργικής**.
      button:
        text: Λήψη Βιογραφικού
        url: uploads/resume.pdf
      headings:
        about: Επαγγελματικό προφίλ
        education: Πτυχία
        interests: Ενδιαφέροντα
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium   # small, medium (default), large, xl, xxl
        shape: circle  # circle (default), square, rounded

  - block: markdown
    content:
      title: "🔬 Ερευνητικά Ενδιαφέροντα"
      subtitle: "Κλινική έρευνα – Καινοτόμες τεχνικές"
      text: |-
        - Χρήση της τεχνητής νοημοσύνης στην Αγγειοχειρουργική
        - Φλεβικές παθήσεις
        - Νέες διαγνωστικές συσκευές
        - Σύνθετα ανευρύσματα αορτής
    design:
      columns: 1

  - block: collection
    id: papers
    content:
      title: Επιλεγμένες Δημοσιεύσεις
      filters:
        folders:
          - publications
        featured_only: true   # Only show items marked as featured
    design:
      view: article-grid      # card, list, article, citation, article-grid
      columns: 2

  - block: collection
    content:
      title: Πρόσφατες Δημοσιεύσεις
      text: ""
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Ομιλίες & Συνέδρια
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: blog
    content:
      title: "Blog / Βίντεο"
      subtitle: ""
      text: ""
      page_type: blog
      count: 5
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]

  - block: markdown
    content:
      title: "📞 Επικοινωνία"
      text: |-
        - 📧 Email: [v.alexiou@aibs.gr](mailto:v.alexiou@aibs.gr)
        - 📱 Κινητό: +30 699 3031 175
        - ☎️ Γραφείο ΠΓΝ Ιωαννίνων: +30 26510 99692
        - 🏥 [Ιατρείο Αγρινίου – Google Maps](https://maps.app.goo.gl/XTBTAhAXWQJPyz7c9)
        - 🧬 [ORCID](https://orcid.org/0000-0003-1388-4880), [Scopus](https://www.scopus.com/authid/detail.uri?authorId=18433424100), [ΕΕΑΕΧ](https://www.vascularsociety.gr/user/vanalex)
    design:
      columns: 1

  - block: markdown
    content:
      title: "🔗 Μέλος Εταιρειών"
      text: |-
        - Ελληνική Εταιρεία Αγγειακής & Ενδαγγειακής Χειρουργικής
        - European Society for Vascular Surgery
        - Ιατρικός Σύλλογος Ιωαννίνων
        - Ιατρικός Σύλλογος Αγρινίου
    design:
      columns: 2
---