# tmpout-reader

Really simple terminal reader for [tmpout](tmpout.sh).

Currently it can only display the first volume
I'll update the script with a volume menu once volume 2 drops.

It uses `curl` to fetch the zine and `less` as a pager.
You can also use `nvim` and `nano` as the pager, just uncomment
the corresponding lines in the script.
Exit the reader using `ctrl + c`.
