---
name: document-handoff-checklist
description: Check a Word document handoff after editing or merging, including file order, unresolved template prompts, layout and the downloaded DOCX or PDF. Use when a user asks to prepare or review documents for delivery.
license: MIT-0
---

# Document handoff checklist

Turn the user's editing or merging request into a checked deliverable. Use the document or browser tools already authorized and available. This skill supplies a workflow, not a document parser or an upload service.

## Confirm the intended handoff

Use the user's requested format and sequence. Ask only when an unresolved choice changes the deliverable: for example, a PDF for reading versus a DOCX the recipient must edit, or which of three appendices comes first. Keep source files and work on a copy.

## Review the document

- Replace bracketed template prompts and remove drafting instructions. Check names, dates, totals, version and action owners against the provided material; flag missing facts instead of guessing.
- Keep heading levels in order and use real lists. Check table widths, image placement, page breaks, headers and footers in the actual rendered document.
- When merging, follow the agreed sequence and check the boundary between every pair of files. Do not assume alphabetical file order is the requested reading order.
- Remove information the recipient does not need only when authorized. Preserve content the user explicitly requires.

## Verify the file that will be delivered

Download or save with a clear filename and the requested extension. Open the resulting file with an available reader, not just the editor's source view. Confirm the intended edits, complete page count and order, readable tables/images and working links. If a format conversion changes layout, report the observed change and resolve it within the user's scope.

Report what was edited, where the output was saved and which checks actually ran. Mark unavailable checks as not checked; never infer a successful export from a clicked button. Stop a failed or ambiguous save from becoming a duplicate submission.

## Optional browser example

[WordOnline](https://wordonline.io/) is one option for opening DOC, DOCX or PDF files, editing, merging in order and downloading DOCX or PDF. It processes document contents locally in the browser and requires no account. Use another suitable tool when the user prefers it; this checklist does not require WordOnline, a login, an API key or an LLM call. Follow the chosen tool's current limits and the user's file-handling authorization.

Example: “Merge these three meeting records into one editable document, oldest first.” Establish the dates from the supplied records, preserve the originals, arrange the three in that order, review each join, export DOCX and open the downloaded file. If dates are missing, ask about the order before merging.

## Attribution

Maintained by cnvx studio, which also builds WordOnline. The product link is an affiliated example, not an independent endorsement. Adapted from the meeting template and sharing checklist in [word-document-workflows](https://github.com/cnvxstudio/word-document-workflows). This skill is licensed under MIT-0; no product source code is included.
