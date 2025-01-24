---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
  url: /images/123_shutterstock_205348522_computerhelp-scaled-e1695910594190.jpg
sections:
  - type: TextSection
    colors: colors-f
    variant: variant-a
    title: MeijComputer.nl
    subtitle: De thuis-expert in ICT
    text: >
      Computer Hulp aan Huis – Met aandacht voor de klant!


      Heb je problemen met je computer? Of loopt je laptop traag en weet u niet
      waarom? Geen zorgen, ik help u graag – gewoon bij u thuis, zonder onnodige
      kosten!


      Wat ik voor u kan doen:


      *   PC of laptop reparaties (hardware en software)


      *   Installeren van programma's of besturingssysteem


      *   Opschonen en optimaliseren voor betere prestaties


      *   Hulp bij internet- of netwerkproblemen


      *   Advies voor upgrades of nieuwe hardware


      Waarom?

      Dit is mijn hobby! Ik vind het leuk om mensen te helpen met hun
      computerproblemen en doe dit zonder winstoogmerk.


      Geen geld? Geen probleem!

      Heeft u niet het geld om een dure ict'er te betalen?

      Dan bent u bij mij aan het juiste adres.

      Als wij geen kosten maken, Maakt u ook geen Kosten.


      Geen ruimte of tijd binnen uw woning? Geen probleem!

      U kunt ook een afspraak maken voor service op onze locatie.


      Interesse? Neem contact met me op voor een afspraak:

      contact:


      *   Max van der Meij -


      *   06 83853062 -


      *   m.vandermeij\@meijcomputer.nl -


      Beschikbaar in Ede, Gelderland. Laat me weten wat u nodig hebt, dan kijk
      ik hoe ik u kan helpen!
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: center
  - type: MediaGallerySection
    title: ''
    subtitle: ''
    images:
      - type: ImageBlock
        url: /images/software-icon-png-29.jpg
        altText: Image one
        caption: Image one caption
        elementId: ''
      - type: ImageBlock
        altText: Image two
        caption: Image two caption
        elementId: ''
        url: /images/text.jpeg
      - type: ImageBlock
        url: /images/R.png
        altText: Image three
        caption: Image three caption
        elementId: ''
    colors: colors-f
    spacing: 91
    columns: 3
    aspectRatio: '1:1'
    showCaption: false
    enableHover: true
    elementId: ''
    styles:
      self:
        height: auto
        width: full
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - type: ContactSection
    title: Hulp nodig? Ik help u graag!
    text: |
      Ik kijk er naar uit om iets van u te horen
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: naam
          label: naam
          hideLabel: true
          placeholder: Voornaam
          width: 1/2
          isRequired: 'true'
        - type: EmailFormControl
          name: Email
          label: Name
          hideLabel: true
          placeholder: Email
          width: 1/2
          isRequired: 'true'
        - type: TextareaFormControl
          name: message
          label: Tell me about your project
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
      submitLabel: Send Message
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
---
