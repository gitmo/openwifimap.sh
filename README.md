# `openwifimap.sh`

Publish a Freifunk node to openwifimap.net on your OpenWRT router.

Depends on the `olsrd-mod-nameservice` and `olsrd-mod-txtinfo` packages.

Only a node with a single interface and a single neighboring hop is currently supported.

Uses BusyBox' built-in netcat for the request, no curl or wget needed.

## See Also

* [openwifimap.net](http://openwifimap.net/)
* [openwifimap HTML5 app](https://github.com/freifunk/openwifimap-html5)
* [openwifimap database API](https://github.com/freifunk/openwifimap-api)

## Credits

* [Gitmo](https://github.com/gitmo)

## Usage

    $ crontab -e
    37 * * * *      /usr/bin/openwifimap.sh

## License

Public domain.
