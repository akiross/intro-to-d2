# Introduzione al Detectron2

Introduzione al Detectron2 - Python Milano 2022-04-28.

Questo repo contiene le slide per il talk per Python Milano, su Detectron2.

L'obiettivo è di mettere in questo repo:

- [x] il link al [video su youtube](https://www.youtube.com/watch?v=VhhM8p23BDs) (grazie ai ragazzi di Crafted Software!);
- [x] slide del talk, per chi volesse guardarsele con cura o sapere come le ho fatte;
- [ ] un tutorial un po' più esteso su come usare D2 (con info sul training).
- [ ] tradurre tutto questo in inglese "4 the gr8r good", ma dubito che troverò il tempo per farlo.

## Slides

Le slides sono fatte con revealjs e qualche immagine. Ho usato una CDN, quindi
per vederle basta fare:

```
cd slides
python3 -m http.server
```

e andare con un browser su [http://127.0.0.1:8000](http://127.0.0.1:8000).

## Licenze

Tutto il contenuto di questa repo è sotto licenza
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/#), per il materiale
che mi appartiene (incluso il logo "shameless plug" di cui vado molto orgoglioso);
elenco qui sotto il materiale che non mi appartiene.

- Le immagini con gli esempi di task arrivano dal
  [repository detectron2](https://github.com/facebookresearch/detectron2).
- Le immagini delle icone delle categorie COCO e le immagini di esempio sono
  prese da [cocodataset.org](https://cocodataset.org/).
- Le icone usate in giro sono prese da [openemoji](https://openmoji.org/).
- L'immagine del LiDAR l'ho rubata su internet, ma non so attribuirne l'origine.
- L'immagine dell'orso nel video arriva da
  [flickr](https://www.flickr.com/photos/tambako/25269050550).
  Purtroppo ho sbagliato e ho creato del materiale derivato anche se la
  [sua licenza non lo permette](https://creativecommons.org/licenses/by-nd/2.0/)!
  Quindi su questo repository ho cambiato quell'immagine con un'altra
  (sempre di me al lago, ma questa volta durante il pranzo), presa da
  [wikipedia](https://commons.wikimedia.org/wiki/File:Bear_Alaska_(3).jpg) e con
  una licenza più permissiva.

Tra l'altro, con i nuovi dati si può vedere come il modello di detection sbagli
nell'individuare due uccelli e un frisbee che non ci sono. Il modello per la
segmentation fa un pochino meglio.
