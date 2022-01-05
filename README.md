[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)

# Update 2022-01-01

I'll be mantaining this repo.

Plans are to keep it simple but if we want to make this work properly we will have to add a bit of extra tooling. At the very least tests to prevent regressions and make sure conversion works as intended.

Perhaps TypeScript and Svelte too. Let me know what you think.

# MySQL to SQLite online converter

Online tool that converts SQL DDL code from MySQL to SQLite format.

Click here to open: https://ww9.github.io/mysql2sqlite/

[![Screenshot](/screenshot.png)](https://ww9.github.io/mysql2sqlite/)

## Why?

I needed to convert a MySQL SQL file to SQLite and couldn't find an online solution. So I wrote one.

## Todo

- [ ] Create tests and make sure they fix current Issues.
- [ ] Create sample SQL for testing.
- [ ] Implement options like `don't remove comments`,  `custom escaping`.

## Problem converting SQL file?

This was tested with only the MySQL SQL file I needed to convert. If the tool doesn't convert your SQL file correctly please [create an issue](https://github.com/ww9/mysql2sqlite/issues). Preferably include the SQL file you're trying to convert or some sample code that's not being converted correctly.

## License

[The Unlicense](http://unlicense.org/), [Public Domain](https://gist.github.com/ww9/4c4481fb7b55186960a34266078c88b1). As free as it gets.
