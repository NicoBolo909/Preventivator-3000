# Preventivator 3000

**Italiano** | [English](README.en.md)

**Preventivi per stampa 3D, dal file al PDF.** Carica i tuoi modelli, ricava peso e tempi dal tuo slicer e ottieni un prezzo basato sui costi reali: materiale, energia, ammortamento della stampante, scarti e manodopera.

![Dashboard di Preventivator 3000](docs/screenshots/dashboard.png)

*Tutti gli screenshot usano dati dimostrativi.*

## Cosa fa

- **Preventivi completi:** clienti, sconti, spedizione, acconto, IVA e servizi extra.
- **Slicing automatico con Bambu Studio, OrcaSlicer o PrusaSlicer:** elabora file 3MF, STL e STEP senza aprire la finestra dello slicer, anche più file insieme.
- **File di qualsiasi slicer:** legge tempo, peso, colori e anteprima dai file già affettati di Bambu Studio, OrcaSlicer, PrusaSlicer (anche .bgcode), Cura (anche .ufp), Simplify3D e ideaMaker.
- **Costi reali:** il costo orario della stampante si calcola da prezzo e vita utile.
- **Anteprima 3D:** posiziona e ruota il modello sul piatto della Bambu Lab A1.
- **Magazzino materiali:** quantità rimaste per bobina e avvisi sotto soglia.
- **Import dallo slicer:** stampanti, materiali e profili di stampa da Bambu Studio, OrcaSlicer o PrusaSlicer.
- **Libreria colori:** importa le tabelle colori in PDF e scegli il colore del materiale con un clic.
- **PDF:** preventivo per il cliente e ordine di lavorazione.
- **Dashboard:** ordini, fatturato, profitto, materiale e ore di stampa.
- **Italiano e inglese:** lingua del programma e dei PDF a scelta.
- **Autosave e aggiornamenti:** salvataggio automatico quando il cliente è selezionato e aggiornamenti all'avvio.

## Il preventivo

Ogni modifica aggiorna subito il riassunto: costi, profitto e totale finale.

![Compilazione di un preventivo](docs/screenshots/preventivo.png)

## Tutti i preventivi

Stato, totale e azioni rapide per aprire, duplicare o esportare in PDF.

![Elenco dei preventivi](docs/screenshots/preventivi.png)

## Materiali e stampanti

![Gestione dei materiali](docs/screenshots/materiali.png)

![Gestione delle stampanti](docs/screenshots/stampanti.png)

## Libreria colori

Importa una tabella colori in PDF, controlla l'anteprima e aggiungila alla libreria. Nel modulo del materiale scegli la linea e clicchi il colore: nome e codice si compilano da soli. Se un PDF non si legge, puoi inserire i colori a mano.

![Libreria colori](docs/screenshots/libreria.png)

![Scelta rapida del colore](docs/screenshots/scelta-colore.png)

## Installazione

**Windows:** scarica `Preventivator3000-Setup` dalle [Release](../../releases/latest) e aprilo. Se Windows mostra "PC protetto da Windows", scegli **Ulteriori informazioni** → **Esegui comunque**: l'installer non ha ancora una firma digitale.

**Mac:** scarica dalle [Release](../../releases/latest) il file `Mac-AppleSilicon.dmg` per i Mac con chip M1, M2, M3 o successivi, oppure `Mac-Intel.dmg` per i Mac con processore Intel. Aprilo e trascina Preventivator 3000 nella cartella Applicazioni. Al primo avvio, se macOS blocca l'app, apri **Impostazioni di Sistema → Privacy e sicurezza** e scegli **Apri comunque**: anche qui manca ancora la firma digitale.

Per lo slicing automatico serve uno slicer installato sullo stesso computer: [Bambu Studio](https://bambulab.com/it/download/studio), [OrcaSlicer](https://github.com/SoftFever/OrcaSlicer/releases) oppure [PrusaSlicer](https://www.prusa3d.com/page/prusaslicer_424/) 2.6 o successivo. Lo scegli in **Impostazioni → Slicer**.

## Licenza

Copyright (c) 2026 Nicolò Casella. Tutti i diritti riservati. Vedi il file [LICENSE](LICENSE).

Bambu Lab, Bambu Studio, OrcaSlicer, Prusa, PrusaSlicer, UltiMaker Cura, Simplify3D e ideaMaker sono marchi dei rispettivi proprietari. Preventivator 3000 è un progetto indipendente.
