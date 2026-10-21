# Java Café SEO deployment notes

The homepage has no documented deployed URL in the project. Before deployment, replace these temporary Open Graph values in `index.html` with the final absolute homepage and image URLs:

- `og:url`: `https://java-cafe.example/`
- `og:image`: `https://java-cafe.example/images/Cafe%20indenfor.jpg`

The placeholder domain is used consistently only because a confirmed production URL was not available.

The Fairtrade definition links to the official Fairtrade Standards page:
`https://www.fairtrade.net/en/why-fairtrade/how-we-do-it/standards.html`

The Ana story uses the supplied local `images/Ana med kaffe.jpg` asset. Its visible caption identifies the image as an illustration and states that the person is not Ana from the fictional example.

The JSON-LD uses fragment identifiers such as `#java-cafe`, `#website`, and `#webpage` because no public production URL is documented. Supply the final absolute homepage URL before publishing if absolute URL properties are required.
