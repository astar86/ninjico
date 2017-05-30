# [Ninjico Framework v.0.0.0](http://www.darthdesigner.com/ninjico.php)
### The first font and CSS framework with multicolored glyphicons

Ninjico Framework is a glyphicons set for scalable vector graphics on websites where it is possible to color the icons sections. The Framework is created and maintained by [Roberto Capasso](http://www.darthdesigner.com).

## List of Files
The following files are included in the framework:
- LICENSE: license file;
- ninjico.css: CSS file to include in your documents;
- ninjico.eot: font file for Microsoft Internet Explorer;
- ninjico.json: json file with the complete list of glyphicons;
- ninjico.min.css: minimized CSS file to include in your documents;
- ninjico.svg: font file for Legacy iOS;
- ninjico.ttf: font file for Safari, Android, iOS;
- ninjico.woff: font file for modern browsers;
- ninjico.woff2: font file for super modern browsers;
- README.me: this file.

## Inclusion
To include the framework in the HTML document, download the package in the ninjico folder and call it through the `<link>` tag into the header of HTML. For example:

```<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Ninjico Exemple</title>
    <link href="ninjico/ninjico.css" rel="stylesheet" />
  </head>
  <body>
    <p>Hello, <i class="nj nj-ninjico"><span></span></i>!</p>
  </body>
</html>
```

## Use
The glyphicons are divided into maximum 4 sections, added to the HTML document using the CSS pseudo-elements `::before` and `::after`. So you need to insert a `<i>` tag with classes `nj` and `nj-*`, where the * symbol indicates the name of the glyphicon. For performance reasons, all glyphicons require a `nj` base class and an individual class. The `<i>` tag must have the `<span>` tag as the only child. For example:

```
<i class="nj nj-ninjico"><span></span></i>
```

The complete list of glyphicons is on [darthdesigner.com](http://www.darthdesigner.com/ninjico.php) or in the ninjico.json file included in the package. You can resize the glyphicons by adding the `nj-size-*` class, where the * symbol indicates the size. By default, each icon has the class `nj-size-md`. The size is reported on [darthdesigner.com](http://www.darthdesigner.com/ninjico.php) or in the list below:
- nj-size-xs
- nj-size-sm
- nj-size-md
- nj-size-lg
- nj-size-xl
- nj-size-xxl
- nj-size-3xl
- nj-size-4xl

You can even color the glyphicons by adding the `nj-color-*` class, where the * symbol indicates the color type. By default each icon has the class `nj-color-mono`. The coloring type is listed on the site or in the list below:
- nj-color-mono
- nj-color-multi
- nj-color-primary
- nj-color-secondary
- nj-color-alternative
- nj-color-trace
- nj-color-debug
- nj-color-success
- nj-color-info
- nj-color-notice
- nj-color-warning
- nj-color-alert
- nj-color-danger
- nj-color-error
- nj-color-emergency
- nj-color-critic
- nj-color-fatal

## Demo
You can find a [demo](http://www.darthdesigner.com/ninjico.php) on the Ninjico Framework web page.

## Browser Support
Ninjico Framework is supported in all modern browsers (Desktop and Mobile). Any Ninjico Framework problem in modern browsers should be reported as a bug.

## License
The Ninjico Framework is licensed under the General Public License v3.0. The license file is included in the package. Please, add the license to the projects where this Framework is used. The license is also available on its creator's site [darthdesigner.com](http://www.darthdesigner.com/ecoSystem/FONT/ninjico/LICENSE). All brand glyphicons are trademarks of their respective owners, the use of these glyphicons in your website does not indicate endorsement of the trademark holder and you can use brand glyphicons only to represent the company or product to which they refer. Please do not use these glyphicons for your logos. Thank you.

## Author
- Email: capasso.roberto.86@darthdesigner.com
- [Twitter](https://twitter.com/Astar_86)
- [Google+](https://plus.google.com/u/0/+RobertoCapasso)
- [Linkedin](https://www.linkedin.com/in/roberto-capasso-300861119/)
- [GitHub](https://github.com/astar86)

