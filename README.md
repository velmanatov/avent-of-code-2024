## Advent of Code 2024

OK. It's time for [Advent of Code 2024](https://adventofcode.com/2024/). From my quick look at the 2023 puzzles I can't see me getting through all 24.
But let's give it a go! I'm still keen to get a taste of different languages and frameworks in the process.
I'll be looking for readable code over performant code and not worrying too much about error handling unless relevant to the puzzle.

### Calendar

1. ["Historian Hysteria"](https://adventofcode.com/2024/day/1) - I completed this in .NET (C#). I use .NET in my job, but on Windows. I set this up on Linux and used VS Code as my IDE to see what that experience was like. Quite honestly it wasn't bad. Would take some getting used to the VS Code tooling. But the cut-down experience might even be preferable. Would be interested to see how well it worked for a larger solution though.
2. ["Red-Nosed Reports"](https://adventofcode.com/2024/day/2) - I've been wanting to try one of these in rust. So gave it a go. Stressed for a long time over the correct way to mutate a vector, removing a single element (which I'm still not happy withs). That plus getting used to syntax in general took me a while!
3. ["Mull It Over"](https://adventofcode.com/2024/day/3) - Solved in python. Got very bogged down in part 2 where I was trying to use a regex to capture a group between do() and don't() and pass that to the function used for part 1. Couldn't get the exact regex magic I needed to do that in the end (also needed to deal with the start of the string differently). So, in the end I went for a manual scan searching for don't() and then do() and flipping a boolean. A tad inelegant, but if I'd gone with something like that from the beginning I'd have saved myself a lot of time!
4. ["Ceres Search"](https://adventofcode.com/2024/day/4) - Used python again. I must have made a meal of it, but Part 1 seemed more laborious today. Constructing diagonals from the grid in particular. Part 2 was quicker to code. I figured we were just looking for all 3x3 blocks in one of four patterns - so just literally started top left and searched every set of 3x3 blocks, checking against those four patterns.