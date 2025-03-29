# Carbonico - Calcolatore di Impronta di Carbonio Digitale

Carbonico è un'applicazione web interattiva progettata per sensibilizzare gli utenti sull'impatto ambientale delle loro attività digitali quotidiane. L'applicazione calcola l'impronta di carbonio digitale basandosi su parametri come lo streaming video, l'utilizzo dei social media, le email e l'archiviazione cloud, offrendo visualizzazioni intuitive e suggerimenti personalizzati per ridurre le emissioni di CO₂.

## 🌱 Funzionalità Principali

### Calcolatore di Impronta Digitale
- Analisi dettagliata delle attività digitali quotidiane
- Parametri personalizzabili per streaming, social media, email, cloud e videochiamate
- Calcolo in tempo reale dell'impronta di carbonio in grammi di CO₂

### Visualizzazioni e Comparazioni
- Dashboard interattiva con rappresentazioni grafiche dell'impatto
- Equivalenti tangibili (distanza in auto, alberi necessari, ore di illuminazione)
- Visualizzazione CO₂ adattiva in base all'entità dell'impronta


### Suggerimenti e Risorse Educative
- Raccomandazioni personalizzate basate sulle abitudini dell'utente
- Sezione dedicata con consigli pratici suddivisi per categoria
- Indicatori di impatto per ogni suggerimento (basso, medio, alto)

## 🛠️ Tecnologie Utilizzate

- **Backend**:
  - [Next.js 14](https://nextjs.org/)

- **Persistenza Dati**:
  - LocalStorage - Per salvare i dati utente

- **Sviluppo**:
  - [TypeScript](https://www.typescriptlang.org/) - Superset tipizzato di JavaScript


## 💻 Requisiti di Sistema

- **Node.js**: v18.17.0 o superiore
- **npm**: v9.6.0 o superiore (incluso con Node.js)
- **Spazio su disco**: Minimo 400MB per l'installazione
- **Browser supportati**: Chrome, Firefox, Safari, Edge (ultime 2 versioni)
- **Dispositivi**: Desktop, tablet e smartphone (design responsive)

## 🚀 Installazione e Avvio

### Installazione Standard

1. **Clona il repository**:
   ```bash
   git clone https://github.com/fr4nc1sr/carbonico.git
   cd carbonico
2. **BUILDA IL DOCKER**:
   ```bash
   docker compose build
   docker compose up

