# Completion plan

1. Define `staffman` from the repository evidence: it currently preserves a landing-page animation export (`demo.html`, one generated image and a JPG reference) rather than a complete staffing/HR application.
2. Establish what Staffman was and what the landing animation represented using README/source/history. Do not infer recruiting, workforce-management or backend functionality from the project name.
3. Determine the export runtime/tool used by the 382 KB `demo.html` and whether the image assets are generated/embedded/external. Document source provenance if an editable master exists elsewhere.
4. Audit the JPG (`9QXEx0uzmeQ.jpg`) and generated image for ownership/licensing before using them in a public portfolio preview.
5. Create a minimal canonical preview wrapper that preserves the historical animation and adds project context without altering the original export.
6. Remove or neutralize obsolete remote scripts/trackers/endpoints in the public preview while preserving a private/original archival copy where appropriate.
7. Add reduced-motion/static fallback, page title/description and pause behavior where the animation runtime allows it.
8. Optimize delivery of the public preview and avoid loading large exported code until the animation enters the viewport or the user opens the demo.
9. Add a smoke check for the exported HTML and referenced images; no application/backend test suite should be fabricated for absent systems.
10. Rewrite README as a verified landing/motion-design case study with historical context, preview instructions, source/export limitations, asset rights notes and explicit scope of work.
