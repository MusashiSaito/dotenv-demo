# dotenv-dev
```
$ npm init
$ touch .env
$ npm install --save-dev dotenv 
$ npm install --save-dev jest
```

## Use .env file
### index.test.js

```
import { config } from 'dotenv';
config();
```

### .env

```
CREDENTIALS=credentials
PROFILE=dev
```

### gitignore

```
node_module
.env
```