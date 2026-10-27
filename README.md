# Principi — la skill per far scrivere a Claude come una persona

Se dai a Claude dei video virali come esempio, prende solo i passi (frase forte, lista numerata, CTA) e li copia alla cieca: il ragionamento che c'è dietro se lo perde. Questa skill gli insegna a ragionare: otto domande da farsi su ogni riga, i segni che fanno sembrare un testo scritto da un'AI con accanto come lo direbbe una persona, e un controllo finale.

L'abbiamo costruita partendo da 340 video brevi analizzati (cosa la gente salva e cosa scorre via) e la usiamo per ogni copione che pubblichiamo.

## Come si usa

1. Scarica questo repository (**Code → Download ZIP**, oppure `git clone`).
2. Aprilo con **Claude Code** (in Codex vale `AGENTS.md`) e scrivi, per esempio:
   - **"scrivimi un copione di 40 secondi su …"**
   - **"rivedi questo copione riga per riga"** (e incolla il testo)
   - **"sembra scritto da un'AI?"**
3. Per usarla in tutti i tuoi progetti, copia la cartella `.claude/skills/principi/` in `~/.claude/skills/`.

## Cosa c'è dentro

```
.claude/skills/principi/SKILL.md               la skill: scrivere, rivedere, controllo voce
.claude/skills/principi/riferimenti/principi.md le 8 domande + cosa salvano le persone (dati)
.claude/skills/principi/riferimenti/voce.md     come parla una persona, come si tradisce l'AI
esempi/copione-del-video.md                     il copione del video in cui la presentiamo
AGENTS.md / CLAUDE.md                           istruzioni per Codex e Claude
```

Vale anche per post e mail, non solo per i video.

Fatto da AutoMate OS · licenza MIT.
