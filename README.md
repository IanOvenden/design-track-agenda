# Design Track Agenda
Responsive design track agenda demo

## Repo
[https://github.com/IanOvenden/design-track-agenda.git](https://github.com/IanOvenden/design-track-agenda.git)

## Requirements

You have a blank canvas on design but the following needs have been identified
- Attendees need to view the agenda ‘at a glance’ on their smart phones during the conference
- Presenters want to display the entire weeks agenda via laptop & projector
- Attendees and presenters want the ability view a single days’ events (‘day in view’)
The design needs to visually distinguish the different categories of events on the design track schedule
- Travel & Registration
- Breaks & Meals
- PegaWORLD main conference events
- Mobile
- User Centered Design
- Customer Centricity
- …All others grouped together

## Constraints

On Wednesday attendees will be split into 2 parallel tracks – the agenda needs to show the split tracks where appropriate
Must support
- iPhone 6 & 7 (iOS 10 & 11)
- Samsung Galaxy (Android 6 Marshmallow & 7 Nougart)
- Web browsers: IE11; Google Chrome; Safari; Firefox
- Comply with minimum WCAG ‘A’ Standard Accessibility.

## Examples

Very much list based:

[Render 2017](https://2017.render-conf.com/schedule)

[Smashing Conf 2018](https://smashingconf.com/schedule/day:thursday)

[FF Conf 2017](https://2017.ffconf.org/sessions)

[Vue.JS Amsterdam](https://www.frontenddeveloperlove.com/vuejsamsterdam/schedule)

## Resources

[Pega Digital Design System](https://patterns-dev.pega.com/)

## Initial Ideas / notes

- Solid HTML structure (should each day be an "article"?
- Service workers - offline support in case connections are unreliable.
- Smooth transitions
- [CSS Grid](https://caniuse.com/#feat=css-grid)
- Flexbox
- BEM
- PWA support for offline caching homescreen shortcut
- Each scheduled item should form a list
- [viewport units](https://caniuse.com/#feat=viewport-units) for height
- Work without Javascript enabled ++
- "js-*" prefix for javascript hook classes
- Transform - need to specify z-index
- Use of [Moqups](https://app.moqups.com/iovenden/NF5q9N8spb/edit/page/ae80896a8) for wireframming
- Rapid prototyping with jQuery - [codepen](https://codepen.io/ianovenden/pen/NXvQgr)
- Ability to add to calendar
- Time and location micro formats
- Discuss technical aspects
- CSS variables

## TODO

- Font loading strategy - most performant
- Automated documentation
- Testing
- Asset copy config for webpack
- CSS Feature detection
- Modernizr for -no-js class to remove the filter
- Sprite map for icons
- Push notifications - session reminders
- Encorporate accessibility checking into build process
- Split build process into dev and prod
- [CSS only filters](https://csswizardry.com/2016/10/pure-css-content-filter/)
- Store the multitrack selected value in session storage