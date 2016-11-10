# trello-config

Contains as a json the configuration that is used by various project
to retrieve information from Hackafe's trello boards.

## Usage

### Node

```
npm install --save hackafe-trello-config
```

```
var boardId = require('hackafe-trello-config').boardId
```

### Remote

```
GET http://trello-config.hackafe.org/config.json
```

## Specification

The package contains a single file [config.json](config.json) formatted as
JSON, with embedded comments following the pattern: `"-//field": "comment"`.
This is to provide maximum compatibility with all the strict json parsers out
there.

## License

[ISC](LICENSE). Copyright (c) [Geno Rouspky](https://github.com/groupsky).
