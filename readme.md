Earthmover provides a way of writing concise, modular programs for
extracting data from messy sources like websites.
It has four components, each of which can be used independently of the others.

**Dumptruck** is a relaxing interface to SQLite. It makes common database commands more concise and Pythonic.

**DieselFuel** is an assortment of helpers for scraping. For example, it provides a function to get options from drop-down box.

**dblist** is a list-like object backed by a plain text file or a SQLite databese. BucketWheel uses it to maintain a stack across scraper runs.

**BucketWheel** abstracts the less variable aspects of scrapers, embeds scraping best practices
and encourages a modular design of scrapers.
