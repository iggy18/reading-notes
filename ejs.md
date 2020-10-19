## google books API

- `q` - Search for volumes that contain this text string. There are special keywords you can specify in the search terms to search in particular fields, such as:
- `intitle`: Returns results where the text following this keyword is found in the title.
- `inauthor`: Returns results where the text following this keyword is found in the author.
- `inpublisher`: Returns results where the text following this keyword is found in the publisher.
- `subject`: Returns results where the text following this keyword is listed in the category list of the volume.
- `isbn`: Returns results where the text following this keyword is the ISBN number.
- `lccn`: Returns results where the text following this keyword is the Library of Congress Control Number.
- `oclc`: Returns results where the text following this keyword is the Online Computer Library Center number.

## EJS

- It's easy to install EJS with NPM.
- `$ npm install ejs`

- Use
- Pass EJS a template string and some data.

- `let ejs = require('ejs');`
- `let people = ['geddy', 'neil', 'alex'];`
- `let html = ejs.render('<%= people.join(", "); %>', {people: people});`