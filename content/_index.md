---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Templergraben 39
      text: Evangelisches Studentenwohnheim
      primary_action:
        text: Get Started
        url: https://hugoblox.com/templates/
        icon: rocket-launch
      secondary_action:
        text: Read the docs
        url: https://docs.hugoblox.com
      announcement:
        text: "Announcing the release of version 1."
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "cyan"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: stats
    content:
      items:
        - statistic: "23"
          description: |
            Mitbewohner*innen
        - statistic: "75+"
          description: |
            Jahre Tradition der Selbstverwaltung
        - statistic: "unter 200€"
          description: |
            Miete monätlich
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]

  - block: features
    id: features
    content:
      title: Wie funktioniert T39?
      text: Das T39 ist im Prinzip eine große WG mit 23 Bewohnern und ein paar Besonderheiten.
      items:
        - name: Miete
          icon: "custom/dollar.png"
          description: Formal ist die Evangelischen Kirche im Rheinland freier Träger des Gebäudes. Das bedeutet, die Kirche ist Eigentümer, verlangt aber keine Abgaben von uns. Weiter haben wir im Gegensatz zu anderen Wohnheimen keine Angestellten wie Reinigungsfachkräfte oder einen Hausmeister. Somit bleiben im wesentliche Grundbesitzabgaben an die Stadt Aachen und die Kosten für Wasser, Strom und Gas.
        - name: Hausarbeiten
          icon: "custom/dollar"
          description: Wie bereits im vergangenen Abschnitt erwähnte, gibt es weder bezahlte Reinigungskräfte, Hausmeister, noch einen Vermieter im herkömmlichen Sinne. Das T39 ist selbstverwaltet, was in Nordrhein-Westfalen einzigartig ist. Dadurch haben wir eine Menge Freiheiten, die zwangsläufig auch mit Verpflichtungen einhergehen. Dazu wird zu Beginn jedes Semesters eine Hausverwaltung aus drei Mitbewohnern gewählt, die Aufgaben verteilt und sich um die Belange des Hauses kümmert.
        - name: Doppelzimmer
          icon: "custom/dollar"
          description: Eine weitere wissenswerte Eigenart des T39 sind die Doppelzimmer im Erdgeschoss. Jeder Neuzugang wohnt für die erste Zeit im Doppelzimmer und zieht erst später in ein Einzelzimmer in eine der oberen Etagen. Obwohl viele Menschen anfangs überrascht darauf reagieren, hat sich dies bis heute bewährt. Die Bewohner haben so die Möglichkeit, in Sachen Gemeinschaft vieles zu lernen. Wichtig sind hier Flexibilität und Sensibilität im Umgang mit anderen Menschen. Dies ist auch der Geist, der als Grundidee über dem T39 schwebt und den enormen Zusammenhalt ausmacht. Die Miete im Doppelzimmer beträgt zurzeit 96 Euro.
        - name: Engagement
          icon: "custom/dollar"
          description: Prinzipiell fallen im T39 verschiedenste Aufgaben an. Wird beispielsweise eine Renovierung beschlossen, werden Ideen gesammelt, die Ausführung und Materialbeschaffung geplant und schlussendlich die Renovierung umgesetzt. Ausserdem gibt es dauerhafte Aufgaben wie die Server Administration oder die Verantwortung für einen der Gemeinschaftsräume. Jeder kann also seine Ideen, Stärken und Projekte umsetzen. Wir freuen uns auf deine.
        - name: Die Gemeinschaftsräume
          icon: "custom/dollar"
          description: Das T39 besteht natürlich nicht nur aus Einzel- und Doppelzimmern. Als Gemeinschaftsräume haben wir unser Wohnzimmer, die Küche und unseren kleinen Garten zur Verfügung. Hier entstehen gemeinschaftliche Aktionen, wie z.B. gemeinsames Kochen, abendliches Zusammensitzen und verschiedene gemeinsam organisierte Feten, wie die jährlich stattfindenden Feuerzangenbowle und Cocktailparty.
  - block: experience
    content:
        work:
        - position: Director of Cloud Infrastructure
        company_name: GenCoin
        company_url: ''
        company_logo: ''
        date_start: 2021-01-01
        date_end: ''
        summary: |
          Responsibilities include:
          - lorem ipsum dolor sit amet, consectetur adipiscing elit
          - lorem ipsum dolor sit amet, consectetur adipiscing elit
          - lorem ipsum dolor sit amet, consectetur adipiscing elit
        
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-experience
    content:
      title: "Experience"
      items:
        - title: "Senior Developer"
          company: "Tech Company"
          location: "San Francisco, CA"
          date_start: "2020-01-01"
          date_end: ""
          description: |
            * Led development of key features
            * Mentored junior developers
            * Improved system performance by 40%
        - title: "Software Engineer"
          company: "Startup Inc"
          location: "New York, NY"
          date_start: "2018-06-01"
          date_end: "2019-12-31"
          description: "Developed web applications using modern technologies"
    design:
      columns: "1"

  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Hugo Smith"
          role: "Marketing Executive at X"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]

  - block: cta-card
    content:
      title: Bewirb dich jetzt
      text: und wird Teil des T39!
      button:
        text: Los geht's
        url: bewerbung.md
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
