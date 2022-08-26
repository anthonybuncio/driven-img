<h1><img src="https://emojis.slackmojis.com/emojis/images/1621038999/39130/toyota-truck.gif?1621038999" width="35"/> Clutched</h1>

> 🚗 Vehicle image REST API

## Usage

For example, to get vehicle information about the Tesla Model X

```sh
http http://localhost:8080/api/v1/tesla/model-x
```

```json
{
  "model-x": {
    "id": 587234957983275,
    "country": "United States",
    "manufacturer": "Tesla, Inc.",
    "region": "North America",
    "serial": "010543",
    "year": 2016,
    "images": {
      "white": "image-url",
      "black": "image-url",
      "blue": "image-url",
      "gray": "image-url"
    }
  }
}
```

## Development

Clone project

```sh
git clone
cd /clutched
```

Install Dependencies

```sh
npm i
```

Start Server

```sh
npm run start
```

## License

Project released under the terms of the MIT [license](./LICENSE).
