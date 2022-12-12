[mdbook](https://github.com/rust-lang/mdBook)  is awesome tool to publish your books online. It offers five themes 
- Light
- Ayu
- Navy
- Coal
- Rust

They are all great but if you are an individual publisher, it gets hard to test your published work in five different themes . Given a multitude of browser/device combinations, it is a lot of work for a single writer to review her work in five different themes and to fine-tune them to suit the needs of the publication. Too much choice :-)

Yellow theme, makes all the theme choices point to a single theme with yellow `#f9ce00` back-ground, with black `Kalam` from Google fonts. The `Kalam` fonts are hibrid of a normal and italics. A creafree font that is good for both English and Hindi — particularly so if you have a mix of both in your publication. Very suitable for poetic quotes common to most of the books !

You can view a usage of this theme at https://gita.shutri.com

How to install - 

- Download the `theme and fonts` folder in `src` folder of your book --> you may git clone this repo and copy paste.
- Point your book.toml to this new theme
```
[output.html]
theme = "src/theme"

```

- Test with `mdbook serve` on local host.

# Credits
- The color choice is inspired from https://demo.diasporamemory.com/
- The cover page and the general css design is inspired from https://ipythonbook.com/
- Google fonts for awesome `Kamal` font

