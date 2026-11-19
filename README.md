# SmartOrder AI — PastaLab

Progetto universitario sviluppato da Sebastiano Nocchi (Università degli Studi di Pavia).

SmartOrder è un prototipo di assistente basato su intelligenza artificiale locale per un piccolo
laboratorio artigianale di pasta fresca. **PastaLab è un caso di studio, non un'attività commerciale reale.**

Il prototipo collega:
- una chat con i clienti (anche tramite WhatsApp Business Platform, in modalità di prova) gestita da un
  modello linguistico open-weight eseguito in locale con Ollama;
- la gestione di ordini, clienti, prodotti e magazzino su PostgreSQL;
- la previsione della domanda e le raccomandazioni di produzione, soggette ad approvazione umana.

Le informazioni su prezzi, ingredienti e allergeni provengono esclusivamente dal database:
il modello non può inventarle.

Stato: prototipo a scopo di validazione accademica. Non vengono trattati dati di clienti reali.
