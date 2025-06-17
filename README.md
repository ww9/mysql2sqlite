[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)

Update: I'm glad this seems to be useful. It's rather limited so please send PRs if you happen to have some improvement ready. Thank you!
I might get back to developing this.

# MySQL to SQLite online converter

Online tool that converts SQL DDL code from MySQL to SQLite format.

Click here to open: https://ww9.github.io/mysql2sqlite/

[![Screenshot](/screenshot.png)](https://ww9.github.io/mysql2sqlite/)

## Why?

I needed to convert SQL database and table creation from MySQL to SQLite and couldn't find an online solution. So I wrote one.

## Updates

- Update 2024-09-24: First contributor PR merged! Thank you! I'll try once again to mantain this repo despite busy life. Improve while keeping it in a simple static single HTML file. If you have suggestions  please submit an issue.
- Update 2022-01-01: I'll be mantaining this repo!

## Todo

- [ ] Create tests and make sure they fix current Issues.
- [ ] Create sample SQL for testing.
- [ ] Implement options like `don't remove comments`,  `custom escaping`.

## Problem converting SQL file?

This was tested with only the MySQL SQL file I needed to convert. If the tool doesn't convert your SQL file correctly please [create an issue](https://github.com/ww9/mysql2sqlite/issues). Preferably include the SQL file you're trying to convert or some sample code that's not being converted correctly.

## License

[The Unlicense](http://unlicense.org/), [Public Domain](https://gist.github.com/ww9/4c4481fb7b55186960a34266078c88b1). As free as it gets.
