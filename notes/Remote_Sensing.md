# Remote Sensing

**Summary**: Notes on satellite imagery, geospatial data products, and Earth observation technology.
**Last updated**: 2026-08-23

---

- [The Technical Debt of Earth Embedding Products](https://cloudnativegeo.org/blog/2026/02/the-technical-debt-of-earth-embedding-products/): Article comparing different earth embeddings. Argues that geospatial foundation model teams excel at training [[Embeddings]] on massive satellite datasets but fail at making them interoperable — each product (Clay, AlphaEarth, Presto, Tessera, etc.) uses different storage formats, coordinate systems, and tile schemes, creating a "distribution tax" paid per product per user. Recommends standardizing on cloud-native formats like GeoParquet and COG. Keywords: earth embeddings, geospatial foundation models, interoperability, GeoParquet, cloud-optimized formats, satellite imagery
