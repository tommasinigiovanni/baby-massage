# 🤍 Guida al Massaggio Neonatale · Baby Massage Guide

> **IT** · Guida interattiva al massaggio neonatale, tratta dagli appunti di un corso post-parto con ostetrica.  
> **EN** · Interactive neonatal massage guide, based on notes from a postpartum course with a midwife.

**Live demo:** [baby-massage.disvel.io](https://baby-massage.disvel.io/)

---

## 🇮🇹 Italiano

### Cos'è

Una guida HTML interattiva — **nessuna dipendenza, nessun framework, un solo file** — pensata per essere salvata sul telefono e consultata durante il massaggio.

Copre due pratiche distinte insegnate nel corso post-parto:

| Sezione | Scopo |
|---|---|
| 🌀 **Massaggio Coliche** | Alleviare il dolore addominale del neonato con movimenti specifici sull'addome |
| 🤍 **Massaggio Corpo** | Rafforzare il legame genitore–figlio attraverso un rito di coccole (scientificamente riconosciuto) |

### Funzionalità

- **Animazioni SVG** per ogni movimento — nessuna immagine esterna
- **Navigazione per parti del corpo** (gambe → braccia → tronco → viso → schiena)
- **Filastrocca delle dita** completa per mani e piedi
- **Nota graduabilità**: non è necessario fare il massaggio completo, specialmente le prime volte
- **Link al video Shantala** di Frédérick Leboyer come riferimento visivo
- Funziona **offline**, salvabile su qualsiasi dispositivo

### Come usarlo

Nessuna installazione necessaria. Apri `guida-massaggio-bimbi.html` direttamente nel browser.

```bash
# Clona il repo
git clone https://github.com/tuo-username/baby-massage-guide.git

# Apri il file
open guida-massaggio-bimbi.html
```

Oppure scarica direttamente il file HTML dalla sezione [Releases](https://github.com/tommasinigiovanni/baby-massage/releases).

### Contenuto

```
baby-massage-guide/
├── guida-massaggio-bimbi.html   # L'intera guida, tutto in un file
├── Dockerfile                   # Serve il file con nginx:alpine
└── docker-compose.yml           # Deploy su Hetzner (rete esterna platform_net)
```

### Deploy con Docker

```bash
docker compose up -d
```

Il contenitore espone la guida su `localhost:3003` tramite nginx.

---

## 🇬🇧 English

### What is this

A single-file interactive HTML guide — **no dependencies, no framework** — designed to be saved on your phone and consulted during the massage.

It covers two distinct practices taught during a postpartum course with a midwife:

| Section | Purpose |
|---|---|
| 🌀 **Colic Massage** | Relieve infant abdominal discomfort with specific abdominal movements |
| 🤍 **Body Massage** | Strengthen the parent–child bond through a mindful touch ritual (medically recognised) |

### Features

- **SVG animations** for every movement — no external images
- **Body-part navigation** (legs → arms → torso → face → back)
- **Complete finger rhyme** for both hands and feet
- **Gradual approach note**: the full massage is not required, especially in the early sessions
- **Link to Shantala video** by Frédérick Leboyer as a visual reference
- Works **offline**, saveable on any device

### Usage

No installation required. Open `guida-massaggio-bimbi.html` directly in any browser.

```bash
# Clone the repo
git clone https://github.com/tuo-username/baby-massage-guide.git

# Open the file
open guida-massaggio-bimbi.html
```

Or download the HTML file directly from the [Releases](https://github.com/tommasinigiovanni/baby-massage/releases) section.

### Contents

```
baby-massage-guide/
├── guida-massaggio-bimbi.html   # The entire guide, all in one file
├── Dockerfile                   # Serves the file with nginx:alpine
└── docker-compose.yml           # Hetzner deployment (external network platform_net)
```

### Deploy with Docker

```bash
docker compose up -d
```

The container serves the guide on `localhost:3003` via nginx.

---

## Credits

Massage techniques taught by a certified midwife during a postpartum course.  
Visual reference: [Shantala by Frédérick Leboyer](https://www.youtube.com/watch?v=PQfDmdv-8Yo).

---

## License

[MIT](LICENSE) — free to use, share, and adapt.  
*If you find it useful, a ⭐ on the repo is always appreciated.*
