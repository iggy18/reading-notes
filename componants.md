# EJS PARTIALS

- you define that reusable bundle of code in a file andinclude it wherever you need it.
- Including a partial in EJS is quite straightforward. You use `<%- include( PARTIAL_FILE_NAME ) %>` where the partial file is relative to the template you use it in.
- partial EJS files are best used for bits of html that will be reused, like headers, footers, nav bars, etc.