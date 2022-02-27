# gamesaves
> Git-backed gamesaves management script.

## Install 

```bash 
$ sudo apt-get install git # /!\ Git is required /!\
$ curl https://raw.githubusercontent.com/MrKloan/gamesaves/master/gamesaves > /usr/bin/gamesaves
$ chmod +x /usr/bin/gamesaves
```

## Usage

```bash
$ export GAMESAVES_ORIGIN=<Your git repository URL>
$ gamesaves -g [GAME_NAME] -p [PATH_TO_SAVES_DIRECTORY]
```
