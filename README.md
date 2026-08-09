Main information comes from the markdown files in the articles folder, one markdown file for each file format. Index.json is used as searchable and presentable front (first 10 formats shown), index.html and script.js, as well as parsing of markdown in markdown-it script and styling in style.css. At this point, no more rare discipline specific file formats are included. So will run on any web server (no jekyll etc.).

The logic for the tags: 

Recommendable: Formats that are open, internationally recognized, and preferred for long-term preservation (e.g., wav, siard, gpkg, ods, eml, zip, mkv).

Migrate: Formats that should be converted to a more secure archival format upon ingest/transfer (e.g., docx and xlsx -> pdf-a or csv).

Debatable: Formats that have significant limitations or risks associated with preservation, but still frequently appear (e.g., standard pdf due to scripting/DRM, and html due to external links).

The search function: please use at least three letters. Please search for file extensions for efficiency (like PNG, tiff, PDF etc.)

The tag "Relevance:" is experimental at this stage. 
