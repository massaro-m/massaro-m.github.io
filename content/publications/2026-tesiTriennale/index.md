---
title: "Sviluppo di un Modello Adattivo per la Mitigazione della Chinetosi Digitale in Ambienti VR"
authors:
- me

# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2026-07-16T00:00:00Z"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["thesis"]

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "Università di Bari and CNR"
  #volume: 1
  #issue: 1

#peer_reviewed: true
#open_access: true
#license: CC-BY-4.0

# Awards, honors, and recognitions. Surfaced as badges on the page and in listings.
# Note: a Test of Time award years after publication uses an explicit `date` that differs from the page date.
#awards:
#  - name: "Test of Time Award"
#    level: winner
#    date: "2025"
#    note: "Awarded for sustained impact 10 years after publication."
#  - name: "Editor's Choice"
#    level: featured

#funding:
#  - funder: "National Science Foundation"
#    grant: "NSF-1234567"

abstract: |
  (ITA) La **chinetosi digitale**, o *cybersickness*, è un fenomeno che può manifestarsi durante l'utilizzo di sistemi di realtà virtuale e comporta sintomi tipici del disorientamento, nausea e malessere generale. La possibilità di prevederla consentirebbe di mettere in atto soluzioni di mitigazione. In questo studio viene sviluppato un modello predittivo basato su tecniche di *Machine Learning* in grado di stimare il livello di chinetosi. In particolare, il modello prevede sia quello corrente raggiunto che una stima del valore futuro. Per tale scopo, è stato prima implementato un esistente modello rule-based, basato su input dati dall'utente tramite controller, usato per generare un insieme di simulazioni che costituiscono i dataset sui quali sono stati addestrati e valutati gli algoritmi di Machine Learning. Sono state confrontate le prestazioni di tre modelli di regressione: Regressione Lineare, Random Forest e XGBoost. In una prima fase sono stati confrontati tutti nella previsione della sola chinetosi corrente, per selezionare quelli da usare per la previsione anche di quella futura. Gli esperimenti eseguiti mostrano che la migliore soluzione è rappresentata dall'XGBoost, con un MAE di 0.02 e un RMSE di 0.03, seguito immediatamente dal Random Forest che ha risultati leggermente inferiori. Lo studio evidenzia che è possibile prevedere il livello di chinetosi con un buon grado di approssimazione, permettendo di anticipare l'applicazione di strategie per la mitigazione e migliorando l'esperienza immersiva degli utenti.

  (ENG) VR sickness, or **cybersickness**, is a phenomenon that can occur while using virtual reality systems and involves typical symptoms of disorientation, nausea, and general discomfort. Predicting it would allow mitigation solutions to be activated. This study develops a predictive model based on *machine learning* techniques capable of estimating the level of cybersickness. Specifically, the model predicts both the current level of cybersickness and an estimate of its future value. To do this, an existing rule-based model was first implemented, based on user inputs via a controller. This model was used to generate a set of simulations that constitute the datasets on which the machine learning algorithms were trained and evaluated. The performance of three regression models was compared: Linear Regression, Random Forest, and XGBoost. Initially, they were compared only for predicting current cybersickness to select those to use for predicting future cybersickness as well. The experiments conducted show that XGBoost performs best, with an MAE of 0.02 and an RMSE of 0.03, closely followed by Random Forest, which performs slightly worse. The study highlights that it is possible to predict the level of cybersickness with a good degree of accuracy, allowing for the earlier application of mitigation strategies and improving the immersive experience for users.

# Summary. An optional shortened abstract.
summary: In collaboration with [**STIIMA** Institute](www.stiima.cnr.it) of CNR (National Research Council)

tags:
 - Virtual Reality
 - VR
 - Cybersickness
 - Artificial Intelligence
 - Machine Learning

featured: false

#hugoblox:
#  ids:
#    arxiv: 1512.04133v1

links: []
  #- type: pdf
    # url: http://arxiv.org/pdf/1512.04133v1
  # - type: code
    # url: https://github.com/HugoBlox/kit
  # - type: dataset
    # url: ""
  # - type: poster
    # url: ""
  # - type: project
    # url: ""
  # - type: slides
    # url: https://www.slideshare.net/
  # - type: source
    # url: ""
  # - type: video
    # url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---