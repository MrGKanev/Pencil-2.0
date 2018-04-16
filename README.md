![Pencil 2.0 logo](https://github.com/MrGKanev/Pencil-2.0/blob/master/assets/logo.png?raw=true) Pencil 2.0
======

A Simple flat-file blog exercise built with plain(procedural) php, no funky frameworks, no fussy builds or installs. And, it comes with a super easy admin panel to edit, delete, create posts and upload images.

The original code isn't my work and it is a fork from syndicatefx's work on Pencil. I wanted to make some huge changes that is why this project was started. 

## Screenshot 

![Pencil 2.0 screenshot](https://github.com/MrGKanev/Pensil-2.0/blob/master/screenshot/screenshot.png?raw=true)

## Install

- You will need PHP running on your server with htaccess and mod_rewrite engine ON capabilities.
- Upload files inside Pencil/ folder anywhere you want to install the blog on your server.
- Edit assets/config.php
- Enable public read+write permissions to "posts/" and "media/"  folders. (chmod 755 or 777)

## Built in functionality:

- SEO friendly url, dynamic page titles and meta descriptions, including Open Graph meta tags.
- Easy configurable site name, author, description/homepage text and copyright text.
- Lightweight WYSIWYG to edit and create new posts, a modified version of [Trumbowyg](http://alex-d.github.com/Trumbowyg).
- Pagination happens on client side built using [jPages](http://luis-almeida.github.com/jPages) jquery plugin.
- No database needed, posts are stored as html in .txt files.

## Things to remember:

- Not equiped for Latin or Cyrillic languages.
- Strict file naming (slug) - always add date first in Y-M-D format, no capitalized letters, dash(-) instead of spaces, when creating new post in admin interface.
- Basic image file upload, you can then insert images in your post using their URL(ex: media/mypic.jpg).
- Admin page not secure, you can use htaccess to password protect this file.
- Strictly Apache + htaccess and mod_rewrite engine on.
- Enable public read+write permissions to "posts/" and "media/"  folders. (chmod 755 or 777)
- Enable public read+write permissions to "posts/" and "media/"  folders. (chmod 755 or 777) - For the posts you write and the images you upload.

## Bugs:

- Fix file sort for same date files, it still outputs the files, but it orders them alphabetically. Probably not a big issue if you're not posting more than one article a day.
- Still testing...

## Acknowledgements:

This project also uses many other open source libraries such as:

<table>
    <tr>
        <td><strong>Project</strong></td>
        <td><strong>License</strong></td>
        <td><strong>Website</strong></td>
    </tr>
    <tr>
        <td>Trumbowyg</td>
        <td>The MIT License</td>
        <td>http://alex-d.github.com/Trumbowyg</td>
    </tr>
    <tr>
        <td>jPages</td>
        <td>The MIT License</td>
        <td>http://luis-almeida.github.com/jPages</td>
    </tr>
</table>

##License

Pencil 2.0  is under the [The MIT License](https://github.com/MrGKanev/Pencil-2.0/blob/master/LICENSE).
