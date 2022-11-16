# Pragati Narrow: FPM Font Package

This repository contains a [fpm font package](https://fpm.dev/featured/fonts/) containing [Google Font: 
Pragati Narrow](https://fonts.google.com/specimen/Pragati+Narrow/about?subset=devanagari).

Pragati Narrow is a libre Devanagari typeface family designed as a complement to [Archivo Narrow](https://fonts.google.com/specimen/Archivo%2BNarrow). It is a sans-serif family with vertical and horizontal cuts. Pragati Narrow comes in 2 weights (Regular and Bold) and was specially developed for screen as webfont and desktop font, too. The Devanagari was designed by Marcela Romero, Pablo Cosgaya and Nicolás Silva. The Latin version of Pragati is reminiscent of late nineteenth century American typefaces. It includes four Narrow styles and four Normal styles (in development), was derived from Chivo (designed by Héctor Gatti) and was developed with the collaboration of the [Omnibus-Type](http://omnibus-type.com/) team.

Pragati (प्रगति) is the Hindi word for ‘progress’.

This project is led by Omnibus-Type, a type foundry based in Argentina. To contribute, visit https://github.com/Omnibus-Type/PragatiNarrow.

Designers: Omnibus-Type, Principal design

Omnibus-Type is a collective typefoundry based in Buenos Aires, Argentina. [Homepage](https://www.omnibus-type.com/)


## How To Use This Font In Your FPM Package:

[Read the docs and demo](https://fifthtry.github.io/pragati-narrow-font).

TLRD:

Include fifthtry.github.io/pragati-narrow-font package into `FPM.ftd` file:

```ftd
-- fpm.dependency: fifthtry.github.io/pragati-narrow-font
```

Inside your `FPM/config.ftd` use the font:

```ftd
-- import: fifthtry.github.io/pragati-narrow-font/assets as pragati-narrow

-- fpm.type.headline-small.font: $pragati-narrow.fonts.Pragati-Narrow
```

Now if in any file you do:

```ftd
-- ftd.text:
role: $fpm.type.headline-small
```

You will see the `pragati-narrow` font.

## 👀 Want to learn more?

Feel free to check [our documentation](https://fpm.dev/) or jump into our [FifthTry Discord 
server](https://discord.gg/bucrdvptYd).

## License

Since Pragati Narrow Font is under [Open Font Licence](https://fonts.google.com/specimen/Pragati+Narrow/about?subset=devanagari), this FPM wrapper is also
under [Open Font License](LICENSE).




