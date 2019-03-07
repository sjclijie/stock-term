# ticker.sh

> Real-time stock tickers from the command-line.

![](https://raw.githubusercontent.com/sjclijie/stock-term/master/screenshot.png)

## Usage

```sh
# Single symbol:
$ ./stock-term.sh sz000034

# Multiple symbols:
$ ./stock-term.sh sz000034 sz000592 sh600297

# Update every five seconds:
$ watch -n 5 -t -c ./stock-term.sh sz000034 sz000592 sh600297
# Or if `watch` is not available:
$ while true; do clear; ./stock-term.sh sz000034 sz000592 sh600297; sleep 5; done
```

