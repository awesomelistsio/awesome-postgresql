# Awesome PostgreSQL [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of awesome libraries, tools, frameworks, and resources for PostgreSQL, an advanced open-source relational database system known for its performance, extensibility, and SQL compliance.

## Contents

- [Libraries and Clients](#libraries-and-clients)
- [GUI Tools](#gui-tools)
- [Backup and Migration](#backup-and-migration)
- [Extensions](#extensions)
- [Optimization and Monitoring](#optimization-and-monitoring)
- [Replication and Clustering](#replication-and-clustering)
- [Data Modeling and Schema Design](#data-modeling-and-schema-design)
- [Learning Resources](#learning-resources)
- [Books](#books)
- [Community](#community)
- [Contribute](#contribute)
- [License](#license)

## Libraries and Clients

- [psycopg2](https://www.psycopg.org/) - The most popular PostgreSQL driver for Python.
- [pgx](https://github.com/jackc/pgx) - A PostgreSQL driver and toolkit for Go that aims to be feature-rich and performant.
- [node-postgres](https://github.com/brianc/node-postgres) - A comprehensive PostgreSQL client for Node.js.
- [JDBC PostgreSQL Driver](https://jdbc.postgresql.org/) - The official JDBC driver for PostgreSQL.
- [SQLAlchemy](https://www.sqlalchemy.org/) - A Python SQL toolkit and ORM that supports PostgreSQL.
- [Diesel](https://diesel.rs/) - A safe and extensible ORM and query builder for Rust, supporting PostgreSQL.
- [ActiveRecord PostgreSQL Adapter](https://guides.rubyonrails.org/active_record_postgresql.html) - The PostgreSQL adapter for Ruby on Rails.
- [BlackVault](https://github.com/venkat22022202/black-vault) - An open-source proxy gateway for managing AI API keys, with AES-256-GCM encryption, cost tracking, and instant revocation, built on Neon Postgres and Drizzle ORM.

## GUI Tools

- [pgAdmin](https://www.pgadmin.org/) - The most popular open-source administration and development platform for PostgreSQL.
- [DBeaver](https://dbeaver.io/) - A universal database tool supporting PostgreSQL and other databases.
- [DataGrip](https://www.jetbrains.com/datagrip/) - A powerful database IDE by JetBrains, with PostgreSQL support.
- [TablePlus](https://tableplus.com/) - A modern, native GUI tool for PostgreSQL and other databases.
- [HeidiSQL](https://www.heidisql.com/) - A lightweight and fast database client for Windows, supporting PostgreSQL.

## Backup and Migration

- [pg_dump](https://www.postgresql.org/docs/current/app-pgdump.html) - The built-in PostgreSQL utility for backing up databases.
- [pgBackRest](https://pgbackrest.org/) - Reliable, flexible backup and restore solution for PostgreSQL.
- [WAL-G](https://github.com/wal-g/wal-g) - A backup and restore tool for PostgreSQL with support for continuous archiving.
- [Flyway](https://flywaydb.org/) - A database migration tool that supports PostgreSQL.
- [Liquibase](https://www.liquibase.org/) - An open-source tool for managing and tracking database schema changes.

## Extensions

- [PostGIS](https://postgis.net/) - A spatial database extender for PostgreSQL, adding support for geographic objects.
- [pg_stat_statements](https://www.postgresql.org/docs/current/pgstatstatements.html) - A module that tracks execution statistics of all SQL statements.
- [pgcrypto](https://www.postgresql.org/docs/current/pgcrypto.html) - A cryptographic extension for PostgreSQL, providing various hashing and encryption functions.
- [TimescaleDB](https://www.timescale.com/) - A time-series database built on top of PostgreSQL.
- [Citus](https://www.citusdata.com/) - An extension that transforms PostgreSQL into a distributed database for horizontal scalability.

## Optimization and Monitoring

- [EXPLAIN](https://www.postgresql.org/docs/current/sql-explain.html) - A command to analyze and optimize query performance.
- [pg_stat_monitor](https://www.percona.com/doc/postgresql/pg-stat-monitor/index.html) - A statistics collection extension for PostgreSQL query performance monitoring.
- [pgHero](https://github.com/ankane/pghero) - A performance monitoring tool for PostgreSQL.
- [pgBadger](https://github.com/darold/pgbadger) - A fast log analyzer for PostgreSQL.
- [PMM (Percona Monitoring and Management)](https://www.percona.com/software/database-tools/percona-monitoring-and-management) - A monitoring tool for PostgreSQL and other databases.

## Replication and Clustering

- [Streaming Replication](https://www.postgresql.org/docs/current/warm-standby.html) - The built-in streaming replication feature of PostgreSQL.
- [Patroni](https://github.com/zalando/patroni) - A high-availability solution for PostgreSQL based on streaming replication.
- [pgPool-II](https://www.pgpool.net/mediawiki/index.php/Main_Page) - A middleware for PostgreSQL that provides connection pooling and load balancing.
- [Bucardo](https://bucardo.org/Bucardo/) - A multi-master replication system for PostgreSQL.
- [Citus](https://www.citusdata.com/) - A distributed database solution for scaling PostgreSQL horizontally.
- [Spock](https://github.com/pgEdge/spock) - Logical multi-master PostgreSQL replication.

## Data Modeling and Schema Design

- [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) - A tool to generate Entity-Relationship (ER) diagrams from PostgreSQL databases.
- [pgModeler](https://pgmodeler.io/) - An open-source database modeler for PostgreSQL.
- [PostgreSQL Schema Design Guide](https://www.postgresql.org/docs/current/ddl.html) - Official PostgreSQL documentation on schema design.
- [DBDiagram](https://dbdiagram.io/) - An online tool for visualizing database schemas, including PostgreSQL.

## Learning Resources

- [PostgreSQL Documentation](https://www.postgresql.org/docs/) - The official PostgreSQL reference documentation.
- [PostgreSQL Tutorial](https://www.postgresqltutorial.com/) - A comprehensive guide to PostgreSQL, covering basic to advanced topics.
- [Leetcode: PostgreSQL Problems](https://leetcode.com/problemset/all/?topicSlugs=postgresql) - Practice SQL queries with PostgreSQL challenges on Leetcode.
- [The Art of PostgreSQL](https://theartofpostgresql.com/) - A blog with articles on advanced PostgreSQL techniques.
- [Postgres Guide](https://postgresguide.com/) - A guide for developers to learn and use PostgreSQL effectively.

## Books

- *PostgreSQL: Up and Running* by Regina Obe and Leo Hsu - A practical guide to using PostgreSQL.
- *Mastering PostgreSQL 15* by Hans-Jürgen Schönig - An advanced book for mastering PostgreSQL.
- *The Art of PostgreSQL* by Dimitri Fontaine - A book focused on advanced PostgreSQL features and techniques.
- *PostgreSQL Cookbook* by Simon Riggs - A collection of practical recipes for PostgreSQL developers.
- *High Performance PostgreSQL* by Gregory Smith - A guide to optimizing PostgreSQL for performance.

## Community

- [PostgreSQL Mailing Lists](https://www.postgresql.org/list/) - The official PostgreSQL mailing lists for discussions and support.
- [Reddit: r/PostgreSQL](https://www.reddit.com/r/PostgreSQL/) - A subreddit for PostgreSQL discussions and questions.
- [Stack Overflow: PostgreSQL](https://stackoverflow.com/questions/tagged/postgresql) - A Q&A site for PostgreSQL-related questions.
- [Planet PostgreSQL](https://planet.postgresql.org/) - A blog aggregator for PostgreSQL posts and news.
- [PostgreSQL Slack Community](https://postgres-slack.herokuapp.com/) - Join the PostgreSQL Slack for discussions and networking.

## Contribute

Contributions are welcome!

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
