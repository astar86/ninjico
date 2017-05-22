# [Ninjico Framework v.0.0.0](http://www.darthdesigner.com/ninjico.php)
### The first font and CSS framework with multicolored glyphicons

Ninjico Framework is a glyphicons set for scalable vector graphics on websites where it is possible to color the icons sections. The Framework is created and maintained by [Roberto Capasso](http://www.darthdesigner.com)

## List of Files
The following files are included in the framework:
- LICENSE: License file;
- README.me: this file;
- ninjico.css: CSS file to include in your documents;
- ninjico.json: Json file with the complete list of glyphicons;

## Inclusion
To include the framework in the HTML document, download the package in ninjico folder and call him through the <link> tag into the header of HTML. For example:

<!DOCTYPE html>
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

## Use
The glyphicons are divided into maximum 4 sections, added to the HTML document using the CSS pseudo-elements ::before and ::after. So you need to insert a <i> tag with classes nj and nj-*, where the * symbol indicates the name of the glyphicon. The <i> tag must have the <span> tag as the only child. For example:

<i class="nj nj-ninjico"><span></span></i>

The complete list of glyphicons is on [darthdesigner.com](http://www.darthdesigner.com/ninjico.php) or in the ninjico.json file included in the package. You can resize the glyphicons by adding the nj-size-* class, where the * symbol indicates the size. By default, each icon has the class nj-size-md. The size is reported on [darthdesigner.com](http://www.darthdesigner.com/ninjico.php) or in the list below:
- nj-size-xs
- nj-size-sm
- nj-size-md
- nj-size-lg
- nj-size-xl
- nj-size-xxl
- nj-size-3xl
- nj-size-4xl

You can even color the glyphicons by adding the nj-color-* class, where the * symbol indicates the color type. By default each icon has the class nj-color-mono. The coloring type is listed on the site or in the list below:
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

## License
The Ninjico Framework is licensed under the General Public License v3.0. The license file is included in the package and please add it to the projects where this Framework is used. The license is also available on its creator's site [darthdesigner.com](http://www.darthdesigner.com/ninjico/license.txt)

## Author
- Email: capasso.roberto.86@darthdesigner.com
- [Twitter](https://twitter.com/Astar_86)
- [Google+](https://plus.google.com/u/0/+RobertoCapasso)
- [Linkedin](https://www.linkedin.com/in/roberto-capasso-300861119/)
- [GitHub](https://github.com/astar86)

