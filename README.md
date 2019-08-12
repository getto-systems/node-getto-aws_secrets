# node-getto-aws_secrets

aws_secrets : getto-psycher vendor plugin

status: production ready

```javascript
const aws_secrets = require("getto-aws_secrets").init({
  region: "AWS-REGION",
  secret_id: "SECRET-ID",
});

const get_values = async () => {
  const json = await aws_secrets.getJSON();
};
```


###### Table of Contents

- [Requirements](#Requirements)
- [Usage](#Usage)
- [License](#License)

## Requirements

- Node.js: 10.16.0


## Usage

```javascript
const aws_secrets = require("getto-aws_secrets").init({
  region: "AWS-REGION",
  secret_id: "SECRET-ID",
});

const get_values = async () => {
  const json = await aws_secrets.getJSON();
};
```

### Install

```bash
npm install --save getto-aws_secrets
```


## License

node-getto-aws_secrets is licensed under the [MIT](LICENSE) license.

Copyright &copy; since 2019 shun@getto.systems

