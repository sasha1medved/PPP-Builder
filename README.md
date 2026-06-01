# PPP Builder

PPP Builder is a browser-based tool for creating Packaging & Packing Process documents.

It helps users enter project information, upload packaging photos, list packaging materials, create packing steps, generate photo descriptions, reload existing PPP files, and export clean PPP documents for review or submission.

## Main File

Open this file in a browser:

`PPP_builder_updated.html`

## How To Use

1. Open the HTML file in a browser.
2. Fill in the Project info section.
3. Supplier name is prefilled as `JENSEN INDUSTRIAL LTD.` but can still be edited.
4. Upload a clear finished packaging photo.
5. Upload a clear parts and materials photo.
6. Add packaging materials and select the materials that should appear in the document.
7. Add packing steps in the correct order.
8. Upload one readable photo for each step, or use bulk upload for all step photos at once.
9. Add descriptions manually, use per-section `Generate description`, or use `Generate All Descriptions`.
10. Click `Submit for Review`, paste (or reuse) the SharePoint folder/library link, then upload the exported file in that folder.
11. Export `PPTX` for editable review and `PDF` for final sharing.

## Load Existing Files

If a PPP needs correction:

1. Click `Load file`.
2. Select a previously exported PPP file from this tool (`.pptx`, `.pdf`, or `.json` draft).
3. Make corrections.
4. Export again.

## AI Description Generator

The tool can generate descriptions from uploaded photos using GitHub Models.

To use it, paste a GitHub token in the Project info page. The token is stored only in browser local storage.

AI is optional. Users can always type descriptions manually.

## Product Lookup

Project Info includes a product lookup field (Matrix ID / Barcode / Description / Cust Ref / Jen Ref).

## Export Output

The exported PPTX and PDF include:

- PowerPoint-style PPP header
- Project information table
- Finished packaging photo
- Parts and materials photo
- Selected material labels
- Packing steps with photos and descriptions

## Notes

- The tool runs locally in the browser.
- No installation is required.
- PPTX and PDF export require an internet connection for export libraries and font loading.
- `Submit for Review` follows a manual SharePoint upload flow (do not forget to allow pop-up windows)
- Use JPG, PNG, WEBP, GIF, or BMP images. Do not upload PDF files as images.
