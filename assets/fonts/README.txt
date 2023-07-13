Hanken Grotesk Variable Font
============================

This download contains Hanken Grotesk as both variable fonts and static fonts.

Hanken Grotesk:

To apply a font to a file we use a typeset.css file. This will point the HTML file to our fonts. 
Within the typeset.css will be an @font-face for each font we would like to use. And the source will 
point to our CDN https://ftvassets.cdn.mmitnetwork.com/templates2/ and the location of the fonts folder for this template.

@font-face {
  font-family: 'Avenir Book';
  src: url('https://ftvassets.cdn.mmitnetwork.com/templates2/Sunny/fonts/Avenir-Book.woff2') format('woff2'),
      url('https://ftvassets.cdn.mmitnetwork.com/templates2/Sunny/fonts/Avenir-Book.woff') format('woff'),
      url('https://ftvassets.cdn.mmitnetwork.com/templates2/Sunny/fonts/Avenir-Book.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}

To start
-----------

1. Upload the font files to transfonter, choose TTF, WOFF and WOFF2 and download the converted file.

https://transfonter.org/

This typeset file has already been created. 