# PPP Builder

PPP Builder is a browser-based tool for creating Packaging & Packing Process PDF documents.

It helps users enter project information, upload packaging photos, list packaging materials, create packing steps, generate photo descriptions, and export a clean PPP document for review or submission.

## Main File

Open this file in a browser:

`ppp_builder_reference_matched.html`

## How To Use

1. Open the HTML file in a browser.
2. Fill in the Project info section.
3. Supplier name is prefilled as `JENSEN INDUSTRIAL LTD.` but can still be edited.
4. Upload a clear finished packaging photo.
5. Upload a clear parts and materials photo.
6. Add packaging materials and select the materials that should appear in the PDF.
7. Add packing steps in the correct order.
8. Upload one readable photo for each step.
9. Add or generate descriptions.
10. Click Export PDF.

## AI Description Generator

The tool can generate descriptions from uploaded photos using GitHub Models.

To use it, paste a GitHub token in the Project info page. The token is stored only in the browser local storage.

AI is optional. Users can always type descriptions manually.

## PDF Output

The exported PDF includes:

- PowerPoint-style PPP header
- Project information table
- Finished packaging photo
- Parts and materials photo
- Selected material labels
- Packing steps with photos and descriptions

## Notes

- The tool runs locally in the browser.
- No installation is required.
- PDF export requires an internet connection for the PDF library and font loading.
- Use JPG, PNG, WEBP, GIF, or BMP images. Do not upload PDF files as images.
