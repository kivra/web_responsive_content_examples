# web_responsive_content_examples

Basic example templates of what you can accomplish when sending sending responsive content in Kivra.

This project is built using [Parcel](https://parceljs.org/), with the help of [PostHTML](https://parceljs.org/languages/html/#posthtml) and [SCSS](https://sass-lang.com/).
When compiled, the output is static self-contained HTML files.

Please refer to the [official documentation for Responsive Content](https://kivra.se/en/business/for-developers/other-flows/responsive-content) for information on how to send the content.

## Directory structure


<ul>
  <li>
    <strong><code><a href="src">src/</a></code></strong> – Source code – HTML and SCSS
    <ul>
      <li>
        <strong><code><a href="src/partials">src/partials/</a></code></strong> – Partial HTML files shared across templates
      </li>
      <li>
        <strong><code><a href="src/templates">src/templates/</a></code></strong> – Base templates to be compiled into self-contained HTML files
      </li>
      <li>
        <strong><code><a href="src/styles">src/styles/</a></code></strong> – CSS (using SCSS) to style the HTML
      </li>
    </ul>
  </li>
  <li>
    <strong><code><a href="dist">dist/</a></code></strong> – Self-contained HTML templates
  </li>
</ul>

## Development setup

Install dependencies:

```shell
npm install
```

## Running locally

```shell
npm start
```

This will start a local server serving the HTML files in `src/templates/` on `http://localhost:1234`.

## Building

```shell
npm run build
```

This will build the templates from the `src/templates/` directory into the `dist/` directory.
