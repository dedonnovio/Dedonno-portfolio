# Viola De Donno's Portfolio

Portfolio statico dedicato ai dipinti e ai progetti di cucito di Viola De Donno.

Il progetto nasce come primo approccio personale al web design durante il percorso di studi presso l'Accademia di Belle Arti. L'obiettivo è creare un sito essenziale, coerente con l'identità visiva del portfolio e consultabile su desktop, tablet e dispositivi mobile.

## Progettazione

Il sito parte dall'analisi e dalla composizione di wireframe realizzati su Figma:

[Apri il progetto su Figma](https://www.figma.com/design/9trZtnqWxteZ5mwOl31Dgh/Progetto-d-esame?node-id=75-396&t=1ZflNMMhWZkDgKtj-1)

Dopo la fase di progettazione sono stati utilizzati strumenti di vibecoding e risorse didattiche di W3Schools per sviluppare la struttura delle pagine in HTML5 e definire il design con CSS3.

## Tecnologie

- **HTML5** per la struttura semantica delle pagine
- **CSS3** per layout, stile, componenti condivisi e responsive design
- **Figma** per wireframe e progettazione visiva
- **Visual Studio Code** come ambiente di sviluppo
- **Git e GitHub** per il versionamento e il caricamento delle modifiche tramite commit e push
- **Vercel** per la pubblicazione online del sito statico

## Pagine principali

Il portfolio è composto da quattro pagine principali:

| Pagina | Descrizione |
| --- | --- |
| `index.html` | Landing page e punto di accesso al portfolio |
| `paintings.html` | Galleria dei dipinti; ogni opera collega a una pagina di dettaglio |
| `sewing-project.html` | Pagina dedicata ai progetti di cucito, raccontati attraverso immagini e storytelling |
| `contacts.html` | Pagina dei contatti, organizzata come un piccolo profilo con i collegamenti a Instagram ed email |

## Struttura del progetto

```text
Dedonno-portfolio/
├── index.html
├── paintings.html
├── sewing-project.html
├── contacts.html
│
├── portfolio/
│   ├── painting-Lei.html
│   ├── painting-mani.html
│   ├── painting-help.html
│   ├── painting-parquet1.html
│   └── ...
│
├── css/
│   ├── base.css
│   ├── header.css
│   ├── footer.css
│   ├── home.css
│   ├── paintings.css
│   ├── painting-detail.css
│   ├── sewing-project.css
│   └── contacts.css
│
└── image/
    ├── pattern_geometrico.png
    ├── Logo sito VD.png
    ├── dipinti/
    └── sewing projects/
```

### Pagine di dettaglio dei dipinti

La cartella `portfolio/` contiene le pagine HTML statiche dedicate ai singoli dipinti. Ogni pagina mostra l'immagine dell'opera, il titolo, le dimensioni, la tecnica e l'anno di realizzazione, oltre ai collegamenti per navigare tra i dipinti.

Tutte le pagine di dettaglio condividono il file `css/painting-detail.css`, così da mantenere uno stile uniforme e rendere più semplice la manutenzione del progetto.

### Fogli di stile

La cartella `css/` è organizzata per componenti e pagine:

- `base.css` contiene il reset e le regole di base condivise
- `header.css` definisce l'header e la navigazione
- `footer.css` definisce il footer e i link social
- `home.css`, `paintings.css`, `sewing-project.css` e `contacts.css` gestiscono il design delle quattro pagine principali
- `painting-detail.css` gestisce il layout delle pagine dedicate ai singoli dipinti

## Responsive design

Il sito è stato sviluppato con media query CSS per adattare layout, immagini, spaziature, header e navigazione a schermi desktop, tablet e mobile.

## Pubblicazione

Il sito è pubblicato tramite Vercel, una piattaforma cloud per il deploy di siti web. Il repository GitHub è collegato a Vercel: dopo un aggiornamento del progetto, le modifiche vengono inviate con `git push` e Vercel può pubblicare automaticamente una nuova versione del sito.

## Autrice

**Viola De Donno**  
Studentessa dell'Accademia di Belle Arti, al suo primo progetto di web design.
