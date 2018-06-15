# WikiMaps

WikiMaps is a wiki-style custom map web app which allows users to create and edit each other's maps.

## Screenshots

!['main page'](https://github.com/ryan-olejnik/Wiki-Maps/blob/master/screenshots/main-page.png)
!['main page'](https://github.com/ryan-olejnik/Wiki-Maps/blob/master/screenshots/map-list.png)
!['main page'](https://github.com/ryan-olejnik/Wiki-Maps/blob/master/screenshots/map-view.png)
!['main page'](https://github.com/ryan-olejnik/Wiki-Maps/blob/master/screenshots/create-new-poi.png)

## Dependencies

- Node.js Express
- Google Maps API
- ['Knex.js'](https://github.com/tgriesser/knex)
- ['Node-sass'](https://github.com/sass/node-sass)


## Getting Started

1. Install dependancies by running the command: `npm install`
2. Fix to binaries for sass: `npm rebuild node-sass`
3. Run migrations: `npm run knex migrate:latest`
4. Run the seed: `npm run knex seed:run`
5. Fire up the server using the command: `npm start`
6. Visit `http://localhost:8080/`
4. Enjoy!
