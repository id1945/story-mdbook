# About

## What is mdBook?

> mdBook is a utility to create modern online books from Markdown files


## Resources

Learn more about [mdBook](https://michaelcurrin.github.io/dev-resources/resources/rust/packages/mdbook.html) in my Dev Resources.


## Structure

- [src/](/src/)
    - [SUMMARY.md](/src/SUMMARY.md) - sidebar contents page. See [SUMMARY.md](https://raw.githubusercontent.com/rust-lang/mdBook/master/guide/src/SUMMARY.md) of mdBook's own site for an example.
    - `*.md` - additional Markdown files as your book's content.
- [book.toml](/book.toml) - mdBook's config file. See [Configuration](https://rust-lang.github.io/mdBook/format/configuration/) in the docs for help on fields.
- `books/` - output directory.