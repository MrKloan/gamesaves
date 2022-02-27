# gamesaves
> Git-backed gamesaves management script.

[![](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-2.png)](http://www.wtfpl.net/)

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
