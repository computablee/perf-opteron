# perf-opteron
A version of Linux Perf that has support for Opteron hardware counters.

## To Build
1. Navigate to `tools/perf`
2. Run `make`
3. Run `./perf --version` to ensure proper build
4. Run `sudo make prefix=INSTALL_LOC install` to your system; I put mine in `/usr/local`
5. Enjoy perf with Opteron counters exposed

## License
I offer this software free of charge with no warranty with whatever requirements are specified by Lord Linus Torvalds.
