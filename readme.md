Earthmover is a framework for writing web scrapers
and other data extractors. It has four components,
each of which can be used independently of the others.

**Highwall** is a relaxing interface to SQLite. It makes common database commands more concise and Pythonic.

**Dumptruck** is an assortment of helpers for scraping. For example, it provides a function to get options from drop-down box.

**dblist** is a list-like object backed by a plain text file or a SQLite databese. BucketWheel uses it to maintain a stack across scraper runs.

**BucketWheel** is the Earthmover's controller. It abstracts the less variable aspects of scrapers, embeds scraping best practices
and encourages a modular design of scrapers.
