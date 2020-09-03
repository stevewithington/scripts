# This is the workflow

1. get imdb ids from scrape.csv
2. request from imdb the character list
3. map characters to actors, get gender from imdb
4. parse script
5. count lines for script character
6. map script character to imdb character

## order of execution

1. movie-to-imdb.js
2. script-download.js
3. imdb-character-scrape.js
4. script-parse.js
5. character-match.js
