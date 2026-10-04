# Hive & NoSQL for Data Warehousing

This project is a static HTML presentation about using Hive and NoSQL concepts in a big-data data warehousing context. It was designed as a workshop/deck for explaining how Hadoop, HDFS, Hive, and analytical data storage fit together.

## Project overview

The presentation covers topics such as:

- Hadoop and HDFS basics
- Why SQL-like querying is needed for large datasets
- What Apache Hive is and how it fits into the data platform
- Hive architecture and metastore concepts
- Hive table storage and file formats
- Partitioning and query workflows
- NoSQL overview and comparison with SQL-based analytics
- Practical data warehouse considerations

## Files included

- `index.html` — the main presentation slide deck
- `logos/` — branding assets used in the slides
- `workshop_hive_nosql-1.pdf` — workshop materials or reference PDF

## How to view the presentation

Because this is a static web page, you can open it directly in any modern browser:

1. Open `index.html` in your browser, or
2. Serve the folder locally with a small web server:

```bash
cd /path/to/this/project
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Notes

- The deck is responsive and designed for presentation-style viewing.
- It includes navigation controls for moving through slides.
- The project is fully front-end based and does not require a build step or framework installation.

## License

This project is intended for educational/workshop use. Please check the repository or local usage context before reusing assets in a commercial setting.
