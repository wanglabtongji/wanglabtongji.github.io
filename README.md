# Chenfei Wang Lab Website

The lab website is built based on [Beautiful Jekyll](https://github.com/daattali/beautiful-jekyll#readme) and [Bootstrap](https://getbootstrap.com/) framework. For `.html` files, you may need to make some HTML-based changes. For `.md` files, both HTML and Markdown are acceptable.

## Pages included

- [Home](#Home)
- [News & Events](#News_and_Events)
- [People](#People)
- [Publications](#Publications)
- [Software](#Software)
- [Positions](#Positions)

## Home
The home page is located at `index.html`. To change the images at the home page, please add or delete the images in the `assets/img/` folder, and then modify the corresponding path in `index.html`.

## News and Events
The news page is located at `pages/news.md`. To add new news, please add new list items on the top.

## People
The people page is located at `pages/people.html`. To add a new person, please add a `lastname_firstname.md` file in `_people/` and add the portrait in `assets/img/people` named by `lastname_firstname.png`. The `md` file should follow the format of `_people/chenfei_wang.md`. To delete people, please remove their `md` file in `_people/`.

## Publications
The publications page is located at `pages/publications.md`. To add new publications, please add new list item on the top, and add the `year_journal_topic.pdf` file in `resources/publications/`.

## Software
The news page is located at `pages/software.md`. To add new software, please add new list items on the top.

## Positions
The positions page is located at `pages/positions.md`. To adjust positions, please modify the file.

