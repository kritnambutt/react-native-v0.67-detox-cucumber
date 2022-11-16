### Install

```
## Install root project
PATH=<root_directory>
yarn

## Install e2e folder
PATH=<root_directory>/e2e
cd e2e
yarn
```

### Running Detox e2e (IOS)
```
PATH=<root_directory>/e2e
cd e2e
yarn build:ios.debug
yarn e2e:iphone.debug
```

### Running Detox e2e (Android)
```
PATH=<root_directory>/e2e
cd e2e
yarn build:android.debug
yarn e2e:android.debug
```