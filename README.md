## This project will be deleted soon!

Due to GitHub's unfortunate new practice of using repositories to train Microsoft LLMs, I have made the difficult decision to migrate all of my projects to [Codeberg](https://codeberg.org/).

Because of this project's low visibility, I have decided that it is not important enough to keep on GitHub.
**Therefore, I have decided to delete this project at some point during the month of September.**
[This project's new home can be found here.](https://codeberg.org/computablee/perf-opteron)

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

## Future Work
Add more counters I guess, the list is not exhaustive right now.
