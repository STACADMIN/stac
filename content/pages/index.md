---
title: Home
slug: /
sections:
  - title:
      text: STAC
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: STUDIO TECNICO AVERSA CAMPAGNA
    text: >+
      un team di professionisti qualificati specializzato in consulenze tecniche
      e progettazione per privati, imprese ed enti pubblici. Con oltre 20 anni
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
      - label: CONTATTACI
        url: /
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
    colors: bg-neutral-fg-dark
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
    type: GenericSection
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/abstract-background.svg
  - title:
      text: IL TEAM
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    people:
      - content/data/person1.json
      - content/data/person4.json
      - content/data/alessandro-iafolla.json
      - content/data/antonio-caselgrandi.json
      - content/data/adriano-piccirillo.json
      - content/data/fabrizio-mauti.json
      - content/data/gianmarco-aversa.json
      - content/data/valerio-kamel.json
      - content/data/ivana-campitelli.json
    variant: four-col-grid
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
    type: FeaturedPeopleSection
seo:
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
isDraft: true
---
