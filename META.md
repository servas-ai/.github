# Meta-Repo-Konzept (Vorschlag)

**Zwei Ebenen, keine Doppelpflege:**

1. **`servas-ai/.github`** – öffentliches Org-Profil (`profile/README.md`): nur Wegweiser, keine Daten.
2. **`Martin-Hausleitner/hans`** – privates Meta-/Wissens-Repo:
   - `research/` – Recherche (Link-Stubs auf Repo-Doku)
   - `modules/` – Submodule: `opencli-connectors`, `opencli-factory`, `matrix-factory`, `paperclip`
3. **`servas-ai/opencli-connectors`** – Hub für alle Connectoren: Ordner-Connectoren direkt, `servas-ai/opencli-*` Einzel-Repos als Submodul unter `repos/` (statt 81 losen Repos), README-Tabelle generiert.

**Konsolidierung:** Vorschlagsliste (behalten/archivieren/zusammenlegen/Submodul) wird von Martin freigegeben; erst dann Ausführung. Nichts wird gelöscht.
