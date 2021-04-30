# Landing builder

In this project we've develop in-house landing page builder for online events. Our main targets were:
- easy to use for project managers
- flexibilty and customization to reach customers' brand books: user can modify colors, fonts, buttons and roundings in any combination
- reliability and zero downtime while update
- be sustainable to high loads during the event
- internationalization

To do all this React JS client was created. It allow us to dynamicaly create sections, pages, elements and styles for all this elements. All information about each event was stored in the single file, that was served by web-server, without any moving parts and DB requests. 

## Stack:

Backend:
- PHP/Symphony
- Vue/gulp
- MariaDB
- Docker + compose

Frontend:
- React/TypeScript
- Redux
- sass and CSS-in-JS
- ESLint for linting and code style checks
- Autobuilds in Phabricator CI
