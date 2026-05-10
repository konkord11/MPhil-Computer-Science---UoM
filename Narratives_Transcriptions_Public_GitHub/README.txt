Narratives_Transcriptions_Public_GitHub
========================================

Pseudonymised narratives intended for a public GitHub repository.
- Export mode: annotations_only (default; GitHub-safe)
- Annotation files: NarrativeXX_Pseudonymized/NarrativeXX_Pseudonymized.annotated.json
- Reversibility / registry metadata is NOT included (see internal research_private).
- Gaza_NamePool_v1.json and config/pseudonymization_manifest.json are omitted from this public bundle (manifest would expose original names; pool withheld for a minimal release).

Regenerate from the private workspace:
  python3 scripts/sync_pseudonymized_narratives.py
  python3 scripts/export_public_github_corpus.py
  (optional: --full-folder --include-binary-media — only after ethics review)

Narrative folders in this bundle: 16

Skipped (no canonical annotation file): 6 — see PENDING_ANNOTATION_no_SABR_file_yet.txt
