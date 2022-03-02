# Flags System Version 1

V1 (originally just called the flags system) was the first version of the flags system. Although V1 was great and did a lot of things well there were many things that it did not support and it was not very flexible. Its successor V2 fixed all or most of the issues BOB had with V1. Today the files in this directory sit unchanged since V1 was put out of service.

There were many reasons that warranted a V2 of the flags system instead of just an update to V1. Among them were:
* The system that maintained and ran V1 sometimes ran into rate limit errors near the end of its use which heavily encouraged BOB to make V2. The exact cause of the errors was never identified before the system was thrown out and a newer better replacement was made.
* BOB had reason to believe that the live updating feature didn't exactly work completely. Although much like the one above, this one was never verified before the system was thrown out.
* V1 only supported overwrites via builds and not specific versions of the game (and it was especially frustrating when new versions were being released to the main build).

Also it is worth noting that most if not all of the `.md` and `.csv` files are outdated compared to the data files due to the bot that maintained them breaking due to a directory change soon before V2 started being worked on.

## Files

`Main-Build.json` is the base file used in all versions of the game and other JSON files that names end with the word overwrite are for specific builds of the game. Each of the overwrite files are applied on top of the base file meaning if there there is a flag referenced in both files the value of the flag in the overwrite file will be used.

There is also some other files that are there for easy reading. They are called `Flags.md` and `Flags.csv` and both of which are automatically compiled by the bot when it makes commits. Those 2 files are virtually the same, the only difference being `Flags.md` takes advantage of markdown and `Flags.csv` just lists everything plainly in a table.

Similar files to `Flags.md` and `Flags.csv` also exist and the ones that end with `.json.md` and `.json.csv` are there for easy reading of a specific JSON file and are sorted alphabetically.