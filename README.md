# Git - Working with Remotes

## Descrizione Progetto

Questo progetto dimostra come lavorare con repository remoti su GitHub utilizzando Git.

## Caratteristiche Principali

- Repository remoti sono versioni del tuo progetto ospitate su Internet
- La collaborazione con altri programmatori implica la gestione di questi repository remoti e il push e pull dei dati
- È fondamentale saper sincronizzare il nostro lavoro locale con un repository remoto

## Comandi Principali

### Visualizzare i server remoti collegati al nostro repository
```bash
git remote -v
```

### Aggiungere o rimuovere un repository remoto
```bash
git remote add <nome> <url>
```

### Caricare il lavoro locale sul repository remoto
```bash
git push <remote> <ramo-locale>
```

### Aggiornare la copia locale del repository, allineandola con la versione remota
```bash
git pull <remote> <ramo-locale>
```

## Struttura del Progetto

- `index.html` - Pagina principale con carousel Bootstrap
- `css/styles.css` - Stili CSS per la pagina
- `js/` - Cartella per i file JavaScript
- `images/` - Cartella per le immagini

## Come Utilizzare

1. Clonare il repository: `git clone https://github.com/Niccolo6874/PrimoEs.git`
2. Navigare nella cartella del progetto
3. Aprire `index.html` nel browser

## Autore

Niccolo Giuliani
