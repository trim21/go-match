# go-match

A string/url matcher

```shell
go get github.com/trim21/go-match
```

## Example

```javascript
match.Match("https://www.example.com/foo/*", "https://www.example.com/foo/v")
match.Match("https?://www.example.org/*.html", "http://www.example.com/index.html")
```

## License

[MIT License](./LICENSE)

forked from https://github.com/tidwall/match
