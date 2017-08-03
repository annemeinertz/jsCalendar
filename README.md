[![latest release](https://img.shields.io/badge/latest%20release-v1.3-green.svg?style=flat-square)](https://github.com/GramThanos/jsCalendar/releases/latest)
[![latest development](https://img.shields.io/badge/latest%20development-v1.4--beta-yellow.svg?style=flat-square)](https://github.com/GramThanos/jsCalendar#whats-new)

# jsCalendar
Just a simple javascript calendar

Visit the jsCalendar site

[https://gramthanos.github.io/jsCalendar/](https://gramthanos.github.io/jsCalendar/)

![preview 1](preview/preview_default.png)

• [Download](https://github.com/GramThanos/jsCalendar/releases/download/v1.3/jsCalendar_v1.3.zip) • [Live preview](https://gramthanos.github.io/jsCalendar/)  • [Documentation](https://gramthanos.github.io/jsCalendar/docs.html)

## Fast set up

Add the jsCalendar code on `<head>`

```html
<link rel="stylesheet" type="text/css" href="jsCalendar.css">
<script type="text/javascript" src="jsCalendar.js"></script>
```

Then insert a calendar on `<body>`

```html
<div class="auto-jsCalendar"></div>
```

## Learn to jsCalendar
- [Getting started](https://gramthanos.github.io/jsCalendar/docs.html#getting-started)
- [Themes](https://gramthanos.github.io/jsCalendar/docs.html#calendar-themes)
	- [Default theme](https://gramthanos.github.io/jsCalendar/docs.html#default-theme)
	- [Material theme](https://gramthanos.github.io/jsCalendar/docs.html#material-theme)
	- [Classic theme](https://gramthanos.github.io/jsCalendar/docs.html#classic-theme)
	- [Theme colors](https://gramthanos.github.io/jsCalendar/docs.html#theme-colors)
- [Parameters](https://gramthanos.github.io/jsCalendar/docs.html#calendar-themes)
	- [navigator](https://gramthanos.github.io/jsCalendar/docs.html#parameter-navigator)
	- [navigator position](https://gramthanos.github.io/jsCalendar/docs.html#parameter-navigator-position)
	- [zero fill](https://gramthanos.github.io/jsCalendar/docs.html#parameter-zero-fill)
	- [month format](https://gramthanos.github.io/jsCalendar/docs.html#parameter-month-format)
	- [day format](https://gramthanos.github.io/jsCalendar/docs.html#parameter-day-format)
	- [first day of the week](https://gramthanos.github.io/jsCalendar/docs.html#parameter-first-day-of-the-week)
	- [language](https://gramthanos.github.io/jsCalendar/docs.html#parameter-language)
- [Javascript Create Calendar](https://gramthanos.github.io/jsCalendar/docs.html#javascript-api-create)
	- [Create calendar](https://gramthanos.github.io/jsCalendar/docs.html#javascript-create-calendar)
	- [Target Element](https://gramthanos.github.io/jsCalendar/docs.html#javascript-calendar-target)
	- [Date ](https://gramthanos.github.io/jsCalendar/docs.html#javascript-calendar-date)
	- [Options](https://gramthanos.github.io/jsCalendar/docs.html#javascript-calendar-options)
- [Javascript Calendar Methods](https://gramthanos.github.io/jsCalendar/docs.html#javascript-api-create)
	- [.next()](https://gramthanos.github.io/jsCalendar/docs.html#javascript-method-next)
	- [.previous()](https://gramthanos.github.io/jsCalendar/docs.html#javascript-method-previous)
	- [.set()](https://gramthanos.github.io/jsCalendar/docs.html#javascript-method-set)
	- [.refresh()](https://gramthanos.github.io/jsCalendar/docs.html#javascript-method-refresh)
	- [.goto()](https://gramthanos.github.io/jsCalendar/docs.html#javascript-method-goto)
	- [.reset()](https://gramthanos.github.io/jsCalendar/docs.html#javascript-method-reset)
	- [.setLanguage()](https://gramthanos.github.io/jsCalendar/docs.html#javascript-method-setLanguage)
- [More javascript things](https://gramthanos.github.io/jsCalendar/docs.html#more-javascript)
	- [Events](https://gramthanos.github.io/jsCalendar/docs.html#more-javascript-events)
	- [Select days](https://gramthanos.github.io/jsCalendar/docs.html#more-javascript-select)
- [More theme things](https://gramthanos.github.io/jsCalendar/docs.html#more-theme)
	- [Custom Colors](https://gramthanos.github.io/jsCalendar/docs.html#more-theme-colors)
- [Add more languages](https://gramthanos.github.io/jsCalendar/docs.html#more-languages)


## Preview images
![preview 3](preview/preview_theme_simple.png)
![preview 4](preview/preview_theme_material.png)
![preview 5](preview/preview_theme_classic.png)


## Whats new?

#### Latest development code v1.4-beta
 - Added
	- jsCalendar.version
	- calendar.clearSelected() alias of calendar.clearselect()
	- calendar.isSelected(date) #3
	- calendar.isVisible(date) #3
	- calendar.isInMonth(date) #3
	- support to get target with selectors

 - Fixed
	- string dates that do not exist throw error
		- ex. `new jsCalendar(document.createElement('div'), "31/2/2017");` now throw error


## Inspiration
I have been using for years javascript libraries like [jQuery](https://github.com/jquery/jquery) and other smaller ones like [ResponsiveSlides.js](https://github.com/viljamis/ResponsiveSlides.js).

So it was time to give back to the community. I just hope this library is helpfull to many people.


## Contact me

Contact us to leave us your feedback or to express your thoughts.

[Open an issue](https://github.com/GramThanos/jsCalendar/issues)

[Send me a mail](mailto:agrammatopoulos@isc.tuc.gr)


## My team

This is a project that I developed for my team,
we are [DinoDevs](https://github.com/DinoDevs), a group of people coding for fun!

DinoDevs members working on this project:
<dl>
  <dt>GramThanos ~ https://github.com/GramThanos</dt>
  <dd>console.log('Hello!');</dd>
</dl>




## Special Thanks

I need to give some attribute to all the people that tested the library and reported the bugs and the mistakes.



## Buy me a beer :beer:

I like beer, you can buy me one by donating to my Bitcoin wallet

My Bitcoin wallet address `173advnPpAgh4UDJXd2TFwTCgAppBKvqKF`



## License

This project is under [The MIT license](https://opensource.org/licenses/MIT).
We do although appreciate attribute.

Copyright (c) 2017 Grammatopoulos Athanasios-Vasileios
