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
        text: Bewirb dich fürs Wohnheim
        url: bewerbung/
      
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "indigo"
        image:
          # Add your image background to `assets/media/`.
          filename: blaueshaus.jpg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
          
  - block: stats
    id: stats
    content:
      items:
        - statistic: "23"
          description: |
            Mitbewohnis
        - statistic: "75+"
          description: |
            Jahre Selbstverwaltung
        - statistic: "100%"
          description: |
            Gemeinschaft
    design:
      # Section background color (CSS class)
      background:
        gradient_mesh:
          enable: true
      columns: "3"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]

  - block: features
    id: features
    content:
      title: Wie funktioniert das T39?
      text: Das T39 ist im Prinzip eine große WG mit 23 Bewohnern und ein paar Besonderheiten.
      items:
        - name: Miete
          icon: hero/wallet
          description: Formal ist die Evangelischen Kirche im Rheinland freier Träger des Gebäudes. Das bedeutet, die Kirche ist Eigentümer, verlangt aber keine Abgaben von uns. Weiter haben wir im Gegensatz zu anderen Wohnheimen keine Angestellten wie Reinigungsfachkräfte oder einen Hausmeister. Somit bleiben im wesentliche Grundbesitzabgaben an die Stadt Aachen und die Kosten für Wasser, Strom und Gas.
        - name: Hausarbeiten
          icon: hero/wrench
          description: Wie bereits im vergangenen Abschnitt erwähnte, gibt es weder bezahlte Reinigungskräfte, Hausmeister, noch einen Vermieter im herkömmlichen Sinne. Das T39 ist selbstverwaltet, was in Nordrhein-Westfalen einzigartig ist. Dadurch haben wir eine Menge Freiheiten, die zwangsläufig auch mit Verpflichtungen einhergehen. Dazu wird zu Beginn jedes Semesters eine Hausverwaltung aus drei Mitbewohnern gewählt, die Aufgaben verteilt und sich um die Belange des Hauses kümmert. Weitere Details siehst Du in unserem <strong><ins><a href="https://wiki.t39.rwth-aachen.de/wiki/index.php?title=Hauptseite"> hausinternen Wiki </a></ins></strong>

        - name: Doppelzimmer
          icon: hero/users
          description: Eine weitere wissenswerte Eigenart des T39 sind die Doppelzimmer im Erdgeschoss. Jeder Neuzugang wohnt für die erste Zeit im Doppelzimmer und zieht erst später in ein Einzelzimmer in eine der oberen Etagen. Obwohl viele Menschen anfangs überrascht darauf reagieren, hat sich dies bis heute bewährt. Die Bewohner haben so die Möglichkeit, in Sachen Gemeinschaft vieles zu lernen. Wichtig sind hier Flexibilität und Sensibilität im Umgang mit anderen Menschen. Dies ist auch der Geist, der als Grundidee über dem T39 schwebt und den enormen Zusammenhalt ausmacht. Die Miete im Doppelzimmer beträgt zurzeit 96 Euro.
        - name: Engagement
          icon: hero/user-group
          description: Prinzipiell fallen im T39 verschiedenste Aufgaben an. Wird beispielsweise eine Renovierung beschlossen, werden Ideen gesammelt, die Ausführung und Materialbeschaffung geplant und schlussendlich die Renovierung umgesetzt. Ausserdem gibt es dauerhafte Aufgaben wie die Server Administration oder die Verantwortung für einen der Gemeinschaftsräume. Jeder kann also seine Ideen, Stärken und Projekte umsetzen. Wir freuen uns auf deine.
        - name: Die Gemeinschaftsräume
          icon: hero/rectangle-group
          description: Das T39 besteht natürlich nicht nur aus Einzel- und Doppelzimmern. Als Gemeinschaftsräume haben wir unser Wohnzimmer, die Küche und unseren kleinen Garten zur Verfügung. Hier entstehen gemeinschaftliche Aktionen, wie z.B. gemeinsames Kochen, abendliches Zusammensitzen und verschiedene gemeinsam organisierte Feten, wie die jährlich stattfindenden Feuerzangenbowle und Cocktailparty.
    design:
      spacing:
          margin: 2 rem

 

# history timeline of T39
  - block: markdown
    id: historie
    content:
      title: Historie des T39
      text: |- 
        <h2>Gründung in den 50er Jahren</h2>  

        1950 ist das T39 ein normales Mietshaus, dass hauptsächlich von Studenten bewohnt wird. Zu der Zeit schließt die Evangelische Kirche, dank der Eigeninitiative der damaligen Mieter (die ersten Bewohner des T39), mit dem damaligem Vermieter einen Vertrag über eine zwölfjährige Miete für den ersten, zweiten und den dritten Stock ab, wo diverse Einzelzimmer, Doppelzimmer und ein Gemeinschaftsräume entstehen.

        <h2>Entwicklung des T39</h2>  

        Nach der Gründung entwickelte sich das T39 dank der Bewohner rasant. Dank vieler Sachspenden und Finanzhilfen konnten sofort nach dem Erwerb des Wohnheims die ersten Renovierungs- und Umbauarbeiten erfolgen. In den folgenden Jahren bis heute fanden zahlreiche weitere Renovierungen statt.
        Im Jahre 1962 fand das erste Hauswochenende in Domburg in Holland statt, eine gemeinsamer Kurzurlaub aller Bewohner ausserhalb von Aachen. Diese Tradition hält sich bis heute.
        Eine weitere Tradition, die sich bis heute hält fand 30 Jahre später im Jahre 1992 ihren Anfang. In diesem Jahr wurden zu ersten Mal im Sommer eine Cocktailparty und als Gegengewicht im Winter die große Feuerzangenbowle veranstaltet. Diese Events werden seitdem Jahr für Jahr im T39 gefeiert.
        Seine charakteristische blaue Farbe erhielt das T39 erst im Jahre 1997. Zwei Jahre später startete mit dem Anschluss an das Hochschulnetz die digitale Revolution. Unseren ökologischen Fußabdruck konnten wir mit der Installation einer Solarthermieanlage auf unserem Dach im Jahr 2009 verbessern.
        Im Jahr 1954 ging der damalige Vermieter in Privatinsolvenz und das Haus wurde Zwangsversteigert. Die Evangelische Kirche entschloss sich dazu, die Immobilie zu erwerben und bekam bei der Versteigerung 1956 den Zuschuss. Das T39 ging für 7000 DM und 3000 DM Gebühren in den Besitz der Landeskirche über.

        <h2>Das T39 heute</h2>  

        Die Tatsache, dass das T39 allein von den Bewohnern verwaltet wird, ist in Nordrhein-Westfalen einzigartig. Das bedeutet für die Bewohner die Chance, eigenständig Entscheidungen zu treffen, Ideen zu verwirklichen und somit die Entwicklung einer eigenen Persönlichkeit.
        Damit das T39 weiter bestehen kann, sind Eigeninitiative und Verantwortung aller Bewohner für sich selbst und für die ganze Gemeinschaft unbedingt erforderlich. Anfallende Arbeiten sollen natürlich nicht nur widerwillig erledigt werden. Aus diesem Grund sind größere Aufgaben in Gruppen aufgeteilt und werden nach Fertigstellung in der Regel gefeiert.
  
  - block: hero
    content:
      title: Bewirb dich jetzt
      text: und wird Teil des T39!
      primary_action:
        text: Los geht's
        url: bewerbung/
      
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "indigo"
        image:
          # Add your image background to `assets/media/`.
          filename: gruppenfoto hv.jpg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: true

---
