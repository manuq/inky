## Install build dependencies

```
pipenv install --dev
pipenv shell
```

Inside the pipenv shell:

```
nodeenv -p --node=14.15.0
npm install -g yarn
yarn global add npm@latest
yarn global add electron-packager
```

## Build

Inside the pipenv shell:

```
./BUILD_FOR_LINUX.sh
```

## Run

```
./Inky-linux-x64/Inky
```
