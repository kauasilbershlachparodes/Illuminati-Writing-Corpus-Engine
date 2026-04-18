https://github.com/user-attachments/assets/66754ea2-9268-4dc3-8db7-869d51232616

# Illuminati Writing Corpus Engine

Illuminati Writing Corpus Engine is a corpus-first intelligence writing system built on an embedded 11-source doctrine base. It does not write like a generic assistant. It reads across the full corpus, ranks evidence, tests competing hypotheses, exposes weak logic, enforces confidence discipline, and compresses complexity into cold, decision-ready judgment.

The system is designed to operate as a non-human analytic engine: BLUF-first, contradiction-aware, source-conscious, and structurally severe. Its core is the complete embedded corpus of intelligence writing, analytic tradecraft, cyber doctrine, and style discipline, treated not as reference decoration but as an active doctrine engine.

## What It Does

- Reads across the embedded 11-source corpus before finalizing in-scope analytic output
- Forces judgment-first structure instead of delayed academic buildup
- Ranks evidence by decision value rather than accumulating facts flatly
- Tests competing hypotheses and exposes weak assumptions
- Applies confidence discipline, source scrutiny, and contradiction checks
- Produces sharper intelligence-style writing with a colder, controlled analytic voice

## Embedded Corpus

The engine embeds the full extracted doctrine base inside the plugin.

Sources included:
- `6-intelligence-writing-tips.txt`
- `analysts-style-manual.txt`
- `analytic-thinking-cia.txt`
- `c2m2-version-2-1-june-2022.txt`
- `cia-writing-guide2017.txt`
- `dia-style-manual-for-intelligence-production.txt`
- `diastylemanualintelprod-2016.txt`
- `intelligence-analysis-reports.txt`
- `intelligence-writing-for-academics.txt`
- `sei-innovation-center-report-cyber-intelligence-tradecraft-project.txt`
- `uwp-handbook-not-to-edit.txt`

Core corpus assets:
- [corpus-index.md](/C:/Users/CIA/Desktop/JOB/plugins/illuminati-writing/skills/illuminati-writing/references/corpus-index.md)
- [corpus-manifest.json](/C:/Users/CIA/Desktop/JOB/plugins/illuminati-writing/skills/illuminati-writing/references/corpus-manifest.json)
- [master-corpus.txt](/C:/Users/CIA/Desktop/JOB/plugins/illuminati-writing/skills/illuminati-writing/references/master-corpus.txt)
- [corpus-mentality-max.md](/C:/Users/CIA/Desktop/JOB/plugins/illuminati-writing/skills/illuminati-writing/references/corpus-mentality-max.md)
- [doctrine-rules.json](/C:/Users/CIA/Desktop/JOB/plugins/illuminati-writing/skills/illuminati-writing/references/doctrine-rules.json)
- [conflict-matrix.md](/C:/Users/CIA/Desktop/JOB/plugins/illuminati-writing/skills/illuminati-writing/references/conflict-matrix.md)

## Analytic Doctrine

The engine is built to behave like a doctrine-driven analytic system, not a stylistic wrapper.

Its operating logic is:
- judgment before background
- evidence before tone
- contradiction before comfort
- rival hypothesis before closure
- confidence by proof, not posture
- implication before ornament

This means the engine is expected to:
- identify the real question early
- collapse noise into hierarchy
- separate known facts from assessed conclusions
- surface the strongest alternative explanation
- compress language without losing analytic meaning
- end with implications, watchpoints, or decision value

## Repository Structure

- `plugins/illuminati-writing/`
  The installable plugin
- `plugins/illuminati-writing/skills/illuminati-writing/`
  Core skill and doctrine files
- `plugins/illuminati-writing/skills/illuminati-writing/references/`
  Embedded corpus, rules, mindset, and reference material
- `research/illuminati-writing/`
  Raw extraction workspace and OCR outputs
- `scripts/`
  Extraction, OCR, rebuild, and packaging scripts
- `dist/`
  Distribution bundle and packaged zip

## Install

Repo-local install:
- Keep the plugin at `plugins/illuminati-writing`
- Keep the marketplace entry at `.agents/plugins/marketplace.json`

Home-local install:
- Copy the plugin to `~/plugins/illuminati-writing`
- Copy or merge the marketplace entry into `~/.agents/plugins/marketplace.json`

Packaged bundle:
- [illuminati-writing-package.zip](/C:/Users/CIA/Desktop/JOB/dist/illuminati-writing-package.zip)

## Build Notes

The corpus was built from extracted and OCR-recovered PDF material.

Support scripts:
- [extract_intelligence_writing_sources.py](/C:/Users/CIA/Desktop/JOB/scripts/extract_intelligence_writing_sources.py)
- [ocr_pdf_windows.ps1](/C:/Users/CIA/Desktop/JOB/scripts/ocr_pdf_windows.ps1)
- [rebuild_extraction_summary.py](/C:/Users/CIA/Desktop/JOB/scripts/rebuild_extraction_summary.py)
- [package_illuminati_writing.ps1](/C:/Users/CIA/Desktop/JOB/scripts/package_illuminati_writing.ps1)

Extraction metadata:
- [extraction-summary.json](/C:/Users/CIA/Desktop/JOB/research/illuminati-writing/extraction-summary.json)

## Operating Rule

Default operating rule:

`Consult and align with the full embedded 11-document corpus before finalizing any in-scope analytic output.`
