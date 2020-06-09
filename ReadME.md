# Rust rest APi 

## GET And POST For RUST using Mysql Jquery Ajax

> Download Project 
## Open project rocket-app 
- open terminal in rocket-app 
- export DATABASE_URL=mysql://username:password@servernamelocalhost/databasename 
-  echo DATABASE_URL=mysql://username:password@servernamelocalhost/databasename > .env
- ROCKET_DATABASES="{ databasename = { url = \"$DATABASE_URL\" } }"                 
- cargo run

### Do not close rocket-app 
- run ./ngrok http 8000
- get your url now lets go to the jquery for Rust open it in another window

## Open project jquery for Rust
- inside index.html jquery section replace localhost:8000 with you ngrok provided url
- open terminal in jquery for Rust 
- surge ./ your domain name
- press enter See the results .

