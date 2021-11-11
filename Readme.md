This repository holds some files that are used by RBAP in a system inspired by Roblox's Fast Flags. `Main-Build.json` is the base file used in all versions of the game and other JSON files that names end with the word overwrite are for specific versions of the game. Each of the overwrite files are applied on top of the base file meaning if there there is a flag referenced in both files the value of the flag in the overwrite file will be used.

There is also 2 other files that are there for easy reading. They are called `FlagsInfo.md` and `FlagsInfo.csv` and both of which are automatically compiled by the bot when it makes commits. Those 2 files are virtually the same, the only difference being `FlagsInfo.md` takes advantage of markdown and `FlagsInfo.csv` just lists everything plainly in a table.