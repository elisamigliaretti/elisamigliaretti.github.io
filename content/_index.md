---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      headings:
        about: ''
        education: ''
        interests: 'Research Interests'
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: collection
    id: papers
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
    design:
      view: citation

  - block: markdown
    id: theses
    content:
      title: Theses
      text: |-
        **2021** — *I composti pindarici: il caso degli hapax legomena nelle Pitiche*
        (“Pindaric compounds: the case of hapax legomena in the Pythians”). MA thesis, Università Cattolica del Sacro Cuore, Milan.

        **2018** — *L’invettiva di Timocreonte di Rodi contro Temistocle (Fr. 727 Page)*
        (“The invective of Timokreon of Rhodes against Themistocles (Fr. 727 Page)”). BA thesis, Università Cattolica del Sacro Cuore, Milan.
    design:
      columns: '1'

  - block: markdown
    id: talks
    content:
      title: Presentations
      text: |-
        **September 2025** — “Latin Verb-Object Compounds: Deep Archaism or (Failed) Borrowing?”
        Charles University, Prague.

        **June 2025** — “Ancient Greek Verb-Initial Compounds as an Inner-Greek Innovation” (with Vasileios Michos).
        11th International Colloquium on Ancient Greek Linguistics, Université Côte d’Azur, Nice.

        **June 2025** — “The Homeric Greek -εσ- ~ -εσι- Alternation in First Compound Member s-Stems.”
        11th International Colloquium on Ancient Greek Linguistics, Université Côte d’Azur, Nice.

        **April 2025** — “Who’s counting? The Indo-European Sky and the Measurement of Time” (with Riccardo Ginevra).
        235th Meeting of the American Society for Premodern Asia, Boston, MA.

        **December 2024** — “A Failed Borrowing Process: the Case of Ancient Greek Verb-Initial Compounds in Latin.”
        4th AMC Symposium: Contact and Language Change, University of Edinburgh.

        **September 2024** — “The Sources of Greek Compounds in -εσι-: A Work in Progress.”
        6th International Summer School for Indo-European Linguistics, Università di Pavia.

        **July 2024** — “Ancient Greek Speech Rhythm.”
        6th Crete Summer School of Linguistics, University of Crete.

        **April 2024** — “Applying for the Position of ‘Resident Poet’: Damophilos in *Pythian* 4.279–299.”
        120th Meeting of the Classical Association of the Middle West and South (CAMWS24), Washington University in St. Louis.

        **October 2023** — “Porson’s Bridge Reconsidered: Aristophanes’ Evidence about Proclitic ἄν.”
        34th Annual UCLA Indo-European Conference (WeCIEC34), University of California, Los Angeles.

        **April 2023** — “Hom. πρόσσω καὶ ὀπίσσω: the Knowledge of the Wise.”
        7th Indo-European Research Colloquium (IERC7), Università Cattolica del Sacro Cuore, Milan.

        **September 2022** — “Pindar and Greek Poetic Language.”
        5th International Summer School for Indo-European Linguistics, Università di Pavia.
    design:
      columns: '1'

  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |-
        All courses at UCLA.

        **Spring 2026** — Teaching Assistant, *Discovering Romans* (Classics 20). Faculty supervisor: Francesca Martelli.

        **Winter 2026** — Teaching Assistant, *Classical Mythology* (Classics 30). Faculty supervisor: Kathryn Morgan.

        **Fall 2025** — Teaching Assistant, *Discovering Greeks* (Classics 10). Faculty supervisor: Richard Ellis.

        **Summer Session A 2025** — Teaching Assistant, *Introduction to the Study of Language* (Ling 1). Faculty supervisor: Stephan Keine.

        **Summer Session A 2024** — Instructor, *Medical Terminology* (Classics 47). Faculty supervisor: David Blank.

        **Winter 2024** — Teaching Assistant, *Introduction to Indo-European Linguistics* (IE/Ling M150). Faculty supervisor: John Clayton.

        **Fall 2023** — Teaching Assistant, *Historical Linguistics* (Ling 110). Faculty supervisor: David Goldstein.

        **Spring 2023** — Teaching Assistant, *Elementary Latin* (Latin 2 Hybrid). Faculty supervisor: Robert A. Gurval.

        **Winter 2023** — Teaching Assistant, *Introduction to the Study of Language* (Ling 1). Faculty supervisor: Giuseppina Silvestri.

        **Fall 2022** — Teaching Assistant, *Elementary Latin* (Latin 1). Faculty supervisor: Robert A. Gurval.
    design:
      columns: '1'

  - block: resume-awards
    id: awards
    content:
      title: Awards
      username: me
    design:
      date_format: '2006'
---
