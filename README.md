# tmpout-reader

Really simple terminal reader for [tmpout](https://tmpout.sh).

To install it just:

```sh
git clone https://github.com/0xBaphy/tmpout-reader
cd tmpout-reader
sudo ln -s `pwd`/tmpout /usr/bin/tmpout
```

Or if you don't feel like cloning this repo:

```sh
curl -s -o tmpout https://raw.githubusercontent.com/0xBaphy/tmpout-reader/main/tmpout
```

Currently it can only display the first volume
I'll update the script with a volume menu once volume 2 drops.

It uses `curl` to fetch the zine and `less` as a pager.
You can also use `nvim` and `nano` as the pager, just uncomment
the corresponding lines in the script.
Exit the reader using `ctrl + c`.
