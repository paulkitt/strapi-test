# Strapi repo with singletyp containing a component

## Login
* `admin@test.com` ' `Secret123!`

## Querying
* Querry the hole single type collection but no media is displayed  `http http://localhost:1337/api/test-page/\?populate\=%2A`
* Querry with explicit populate param for the content component `http http://localhost:1337/api/test-page/\?populate\[content\]\[populate\]\=%2A`
* Querry with explicit populate param for the head component    `http http://localhost:1337/api/test-page/\?populate\[head\]\[populate\]\=%2A`
