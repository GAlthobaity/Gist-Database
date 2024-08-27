Gist Database
===============
  *This project is part of the [INE](my.ine.com) x [SDA](https://t.co/zI6rJymObV) Data Science Program, [Intro to Databases with Python](https://my.ine.com/DataScience/courses/5c32f91c/intro-to-databases-with-python).*

This project integrates the requests library (HTTP) with databases (sqlite3). It utilizes requests to interact with GitHub's API, retrieves gists, and stores them in a database for searching.

## Features

- The ***`importer`*** fetches gists from GitHub using a specified username and inserts them into the database. It supports an optional commit parameter to automatically commit changes.

- The ***`searcher`*** retrieves gists from the database based on various filters. By default, it returns all gists, but it can filter results by GitHub ID and creation date.

- Searches involving *datetime fields* with various comparison operators. Users can filter gists based on creation and update dates using operators such as greater than, less than, etc.
