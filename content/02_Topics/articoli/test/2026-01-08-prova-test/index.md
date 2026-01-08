---
title: "TEST — Nota di prova per pipeline Djungō"
topic: test
subtopic: pipeline
status: draft
date: 2026-01-08
slug: prova-pipeline-djungo
---

## Scopo
Questa nota serve a verificare l’intero flusso:
Obsidian (source) → django_vault/PUBLIC → django-vault-public/content → build docs/ → GitHub Pages.

## Contenuto (mini-articolo)
### 1) Un’idea in una frase
La qualità di una pipeline si misura da quanto è noiosa: più è ripetibile, meno produce sorprese.

### 2) Tre punti di controllo
- Il file è in `django_vault/PUBLIC/02_Topics/.../index.md`
- Dopo l’export esiste in `django-vault-public/content/02_Topics/.../index.md`
- Dopo il build esiste in `django-vault-public/docs/.../index.html`

### 3) Chiusura
Se vedi questa pagina su GitHub Pages, la pipeline è OK.
