---
type: PageLayout
title: Home
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: STAC
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: STUDIO TECNICO AVERSA CAMPAGNA
    text: >+
      un team di professionisti qualificati specializzato in consulenze tecniche
      e progettazione per privati, imprese ed enti pubblici. Con oltre \[X] anni
      di esperienza nel settore, offriamo una vasta gamma di servizi legati
      all'edilizia, al catasto e alla gestione immobiliare.


      **I nostri servizi includono:**


      *   **Progettazione e Direzione Lavori:** Dalla progettazione
      architettonica alla gestione completa del cantiere, garantiamo soluzioni
      su misura, sicure e conformi alle normative vigenti.


      *   **Pratiche Catastali e Topografiche:** Gestione delle pratiche
      catastali, aggiornamenti cartografici, frazionamenti e rilievi topografici
      di precisione.


      *   **Certificazioni e Consulenze:** Certificazioni energetiche, perizie
      tecniche e valutazioni immobiliari, consulenze per ristrutturazioni e
      riqualificazioni energetiche.


      *   **Gestione Immobiliare:** Assistenza tecnica per la compravendita di
      immobili, pratiche di successione, frazionamenti e accatastamenti.


      Il nostro obiettivo è fornire un servizio professionale, puntuale e
      trasparente, seguendo il cliente in ogni fase del progetto, dal concept
      iniziale alla realizzazione finale. Affidati a noi per trovare soluzioni
      innovative e di alta qualità, che valorizzino il tuo patrimonio
      immobiliare.


      Contattaci per una consulenza o per saperne di più sui nostri servizi.



    actions:
      - type: Button
        label: CONTATTACI
        url: /
        icon: arrowRight
        iconPosition: right
        style: primary
    colors: bg-neutral-fg-dark
    backgroundImage:
      type: BackgroundImage
      url: /images/abstract-background.svg
      altText: Placeholder image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
  - type: FeaturedPeopleSection
    title:
      type: TitleBlock
      text: Meet the team
      color: text-dark
      styles:
        self:
          textAlign: center
    people:
      - content/data/person1.json
      - content/data/person2.json
      - content/data/person3.json
      - content/data/person4.json
      - content/data/person5.json
      - content/data/person6.json
    actions: []
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Open positions
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: Subtitle goes here
    items:
      - type: FeaturedItem
        title: Account Executive
        subtitle: Sales
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: Open Source Engineer
        subtitle: Marketing
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: Senior Software Engineer
        subtitle: Engineering
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
    actions:
      - type: Button
        label: Apply now
        url: /
        icon: arrowRight
        iconPosition: right
        style: primary
    variant: toggle-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-3
          - pr-3
        justifyContent: center
      subtitle:
        textAlign: center
slug: /
seo:
  type: Seo
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify.
  metaTags: []
---
