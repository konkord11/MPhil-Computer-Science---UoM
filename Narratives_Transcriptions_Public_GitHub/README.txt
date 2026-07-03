Narratives_Transcriptions_Public_GitHub
========================================

Pseudonymised narratives intended for a public GitHub repository.
- Export mode: annotations_only (default; GitHub-safe)
- Annotation files: NarrativeXX_Pseudonymized/NarrativeXX_Pseudonymized.annotated.json
- Reversibility / registry metadata is NOT included (see internal research_private).
- Name pool (Gaza_NamePool_v1.json) and pseudonymization_manifest.json are NOT included by default (manifest lists originals; use --include-pseudonymization-artifacts only for controlled internal copies).

Regenerate from the private workspace:
  python3 scripts/sync_pseudonymized_narratives.py
  python3 scripts/export_public_github_corpus.py
  (optional: --full-folder --include-binary-media — only after ethics review)

Narrative folders in this bundle: 30

Skipped (no canonical annotation file): 12 — see PENDING_ANNOTATION_no_SABR_file_yet.txt
