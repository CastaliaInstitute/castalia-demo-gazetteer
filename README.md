# Castalia Gazetteer Member Archive

This repository stores one household's private Castalia Gazette and Gazetteer outputs.

## Layout

```text
castalia-member.json
outputs/YYYY-MM-DD/gazette.pdf
outputs/YYYY-MM-DD/pupils/{pupil_key}/gazetteer.pdf
outputs/YYYY-MM-DD/pupils/{pupil_key}/art-sheet.pdf
outputs/YYYY-MM-DD/pupils/{pupil_key}/manifest.json
```

## Generate

Use **Actions -> Generate Castalia Gazetteer -> Run workflow**.

Required repository secrets:

- `GEMINI_API_KEY` for daily Gazette content.
- `CASTALIA_GAZETTEER_TOKEN` if `CastaliaInstitute/gazetteer` is private.

The workflow commits generated PDFs back to this private repository.

