# SQL

**Summary**: Notes on SQL, spatial SQL, and query optimization across database engines.
**Last updated**: 2026-08-23

---

- [Optimizing DuckDB Spatial Queries](https://www.geomermaids.com/cookbook/duckdb-spatial/): Translates PostGIS spatial join patterns to DuckDB, showing that while both produce identical results, DuckDB needs explicit optimization since it doesn't fold spatial indexing into query planning automatically the way PostGIS does — using constant-geometry predicates for R-tree index usage, avoiding multiple spatial predicates per join, and choosing indexed lookups for small datasets versus parallel spatial joins for large-scale enrichment. Also covers GeoParquet pruning. See also [[Data]]. Keywords: DuckDB, spatial SQL, PostGIS, query optimization, R-tree index, GeoParquet
