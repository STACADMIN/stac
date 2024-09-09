---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: STAC
      color: text-dark
      type: TitleBlock
    subtitle: STUDIO TECNICO AVERSA CAMPAGNA
    text: >+
      Un team di professionisti qualificati specializzato in consulenze tecniche
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
      - label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: See Tutorials
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: ''
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: auto
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
  - title:
      text: Generic Section With A Form
      color: text-dark
      type: TitleBlock
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
