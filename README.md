# PandaLogica brand assets

This repository is the single source for PandaLogica's official visual assets. The approved logo is [`logos/pandalogica-logo.png`](logos/pandalogica-logo.png). The image is a 1024 × 1024 PNG supplied by the owner, with a white background.

## Structure

- [`logos/`](logos/README.md): official logo files and their usage notes.

## Use in PandaLogica projects

Reference the canonical asset through a version-pinned URL. Replace the commit hash when an approved logo revision is published, so each consumer chooses when to update. For example:

```text
https://raw.githubusercontent.com/pandalogica/brand-assets/<commit>/logos/pandalogica-logo.png
```

A browser or application using this URL needs network access to GitHub's raw-content host. Keep a reviewed local fallback if that availability requirement is unacceptable for a production consumer.

## Changes

Treat logo changes as brand decisions: open an issue, attach the proposed source, record approval, and review the rendered asset before updating the file. Keep the existing path for approved replacements so consumers can update their pinned commit without changing paths. Do not add unapproved variants or duplicate the official file in this repository.

The assets are PandaLogica brand material. Public visibility makes them retrievable; it does not state reuse terms for unrelated projects. Contact PandaLogica for permission outside its projects.
