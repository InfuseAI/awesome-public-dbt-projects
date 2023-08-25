# Awesome Public dbt Projects 🌟

A curated list of awesome public dbt (Data Build Tool) projects that the community can learn from. If you have a dbt project or know of one that should be included, please submit a pull request!

## Table of Contents

- [Introduction](#introduction)
- [Projects](#projects)
- [Contribution Guidelines](#contribution-guidelines)
- [License](#license)

## Introduction

dbt (Data Build Tool) is a powerful tool for transforming data in the data warehouse. This repository aims to gather public dbt projects that can serve as references, inspirations, or learning materials for the community.

## Projects

1. **[Spellbook](https://github.com/duneanalytics/spellbook)** - A collection of SQL views for Dune. It serves as Dune's interpretation layer, built for and by the community, using the dbt (data build tool) framework. The repository contains models that transform raw and decoded records into interpretable blockchain data. Contributors can add or modify "spells" (SQL queries) and test them against Dune's engine. The project encourages collaboration, with guidelines for contributing and testing provided.
2. **[CountMoney](https://github.com/flyanakin/CountMoney)** - A low-cost finance data pipeline orchestration tool that requires only Python & SQL. It utilizes modern data stack components, with Dagster as its core orchestration tool. Data sources include Tushare for finance data and Airtable for other data. The system manages data extraction, loading, transformation (via dbt), and visualization. Notifications can be received through wxwork webhook and email.
3. **[Danish Democracy Data](https://github.com/bgarcevic/danish-democracy-data)** - A personal hobby project aimed at creating a data warehouse for the Danish parliament's data. It utilizes open-source tools and primarily sources data from the Folketinget API. The project is written in Python and provides instructions for setting up and running the data extraction and transformation processes. The repository structures data into raw and curated formats, and it uses dbt (data build tool) for data transformation.
4. **[Taiwan Campaign Finance](https://github.com/g0v/tw_campaign_finance)** - It focuses on Taiwan's campaign finance data and uses dbt and duckdb for data modeling and transformation. The project requires users to download income and expenditure CSV data from a provided link. After processing, the resulting parquet files are stored in the "target" directory. The repository also includes a "vgplot" directory for interactive data exploration using the Mosaic tool.


## Contribution Guidelines

1. **Fork** the repository on GitHub.
2. **Clone** the forked repository to your local machine.
3. **Commit** your changes to your own branch.
4. **Push** your work back up to your fork.
5. Submit a **Pull request** so that we can review your changes.

NOTE: Be sure to merge the latest from "upstream" before making a pull request!

## License

This repository is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
