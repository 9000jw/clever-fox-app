---
title: 'Bewerbung'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: features
    content:
      title: "Schön, dass du interessiert bist!"
      items:
        - name: "Was wir Dir bieten"
          icon: "hero/sparkles"
          description: |
              - Eine ganz besondere Riesen-WG-Atmosphäre.
              - Teilzuhaben am einzigartigen Projekt "selbstverwaltetes Wohnheim".
              - Jede Menge Spass.
              - Die Möglichkeit viele nette Menschen aller möglichen Nationalitäten und Konfessionen kennenzulernen.

        - name: "Dein Profil"
          icon: "hero/user"
          description: |
              - Du bist aufgeschlossen und hast Lust auf das WG-Leben.
              - Du zeigst Interesse an deinen Mitbewohnern und ziehst nicht nur dein eigenes Ding durch. Das T39 ist kein Hotel
              - Du bist bereit dich für das Wohnheim einzusetzen und deinen Anteil der regelmäßig anfallenden Hausarbeiten gerne und gewissenhaft zu übernehmen.
              - Du bist eingeschriebene/r Student/in.
              - Du bist bereit, dich selbständig und eigenverantwortlich fär das Haus zu engagieren, auch wenn dies über deine normalen Pflichten hinausgehen sollte. Das T39 lebt davon, dass sich jeder einbringt und auch mal mehr macht als unbedingt notwendig.
              - Du kannst dich gut auf Deutsch verständigen.
      design:
        columns: 2
        spacing:
          margin: 2 rem
        container: fixed
        align: center
        css-class: "row-cols-1 row-cols-md-2 justify-content-center"

  - block: cta-card
    content:
      title: Interesse?
      text: dann fülle bitte das Bewerbungsformular aus (nur mit dem, was du preisgeben möchtest). Wenn du möchtest, füge einen Lebenslauf an und schick uns bitte das Ganze an  hv@t39.rwth-aachen.de.
      button:
        text: "Bewerbungsformular"
        icon: "arrow-down-tray"
        url: bewerbung.pdf
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
  - block: markdown
    content:
      title: 
      text: |
          {{% callout note %}}
          Bewerbungen, die nicht auf unserem Pflicht-Bewerbungsformular abgegeben und nicht auf Deutsch geschrieben wurden, werden nicht berücksichtigt.

          Nach einer Vorauswahl werden einige Bewerber/innen zum Bewerbungsgespräch eingeladen, wo auch die freien Zimmer besichtigt werden können. Wenn wir dich einladen, erhalten alle Mitbewohner deine Bewerbung, um dich schon mal etwas kennenzulernen. Nach den Bewerbungsgesprächen entscheidet die Hausverwaltung, an wen die Zimmer vergeben werden. Über diese Entscheidung werden die Bewerber/innen per E-Mail informiert. Bei uns gibt es keine Warteliste.
          {{% /callout %}}
      background:
        color: "white"
      
---
