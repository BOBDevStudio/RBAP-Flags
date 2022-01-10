| Key | Type | Value |
|-|-|-|
| CommaAvoiderFlag | String | This is a special flag as it is ignored by the flags system. It is just here so I don't have to worry about commas. |
| DockEnabled_ServerControlDock | Bool | true |
| DockEntrance_BarriersDisabled | Bool | false |
| DonationsDock_OpenOutsideMain | Bool | true |
| FlagsSystem_UpdateCheckTime | Number | 60 |
| Game_ForcedTemporarilySavedDataExpiration | Number | 60 |
| Game_ForceTemporarilySavingData | Bool | true |
| ServerInfo_RunTimeDisplayExactSeconds | Bool | true |
| ServerInfo_RunTimeDisplaySeconds | Bool | true |

### Type Key:

* `Bool` - A value of true or false.
* `String` - Just a normal string with nothing special about how the flags system uses it.
* `Number`
* `Color` - A string encoded so it tells the flag system that its value should be a color. The bot automatically transfers it into the `rgb(Red, Green, Blue)` format for easy reading.
* `(Remove Code) String` - A string that is the same as the remove code which tells the flag system when an overwrite file is used that flag should not exist.
* `Table` - A list of values optionally defined by keys.