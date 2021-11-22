| Key | Type | Value |
|-|-|-|
| AvatarEditor_DebugOutputsEnabled | Bool | false |
| AvatarEditor_Enabled | Bool | false |
| ChatCommandEnabled_Mute | Bool | true |
| CommaAvoiderFlag | String | This is a special flag as it is ignored by the flags system. It is just here so I don't have to worry about commas. |
| DockEnabled_BloxyStatueReMadeDock | Bool | true |
| DockEnabled_BobTheMobDock | Bool | true |
| DockEnabled_CampFireDock | Bool | true |
| DockEnabled_ColorBlocksDock | Bool | false |
| DockEnabled_ColorMixerDock | Bool | false |
| DockEnabled_ConstructionBarrierDock | Bool | true |
| DockEnabled_DonationsDock | Bool | true |
| DockEnabled_EventsDock | Bool | false |
| DockEnabled_GameInfoDock | Bool | true |
| DockEnabled_GameRoomsDock | Bool | true |
| DockEnabled_IceCubeTrayDcok | Bool | true |
| DockEnabled_IndustrialLightDock | Bool | true |
| DockEnabled_LighthouseDock | Bool | true |
| DockEnabled_MineDock | Bool | true |
| DockEnabled_MovingSpotlightDock | Bool | true |
| DockEnabled_NoStandingJokeDock | Bool | true |
| DockEnabled_NPCsKeyDock | Bool | true |
| DockEnabled_OldGameRoomsDock | Bool | true |
| DockEnabled_RainbowDanceFloorDock | Bool | true |
| DockEnabled_RobloxIconsDock | Bool | true |
| DockEnabled_ServerAndGameInfoDock | Bool | false |
| DockEnabled_ServerControlDock | Bool | false |
| DockEnabled_Stage | Bool | true |
| DockEnabled_UpdateLogsDock | Bool | false |
| DockEnabled_WeirdHillsDock | Bool | true |
| DockEnabled_WheelOfOdditiesDock | Bool | true |
| DockEnabled_WindowShowcaseDock | Bool | true |
| DockEnabled_WindowShowcaseV2Dock | Bool | true |
| DonationsDock_FireworksEnabled | Bool | false |
| DonationsDock_OpenInStudio | Bool | true |
| DonationsDock_OpenOutsideMain | Bool | false |
| FavoriteColor_BOB | Color | rgb(0, 255, 255) |
| FavoriteColor_Unbitterness | Color | rgb(71, 13, 83) |
| Files_DevBuildGameVersion | String | Game-Version/Dev-Build |
| Files_DevBuildListedUpdateLogs | String | Listed-Update-Logs/Dev-Build |
| Files_ImagingBuildGameVersion | String | Game-Version/Imaging-Build |
| Files_ImagingBuildListedUpdateLogs | String | Listed-Update-Logs/Imaging-Build |
| Files_MainBuildGameVersion | String | Game-Version/Main-Build |
| Files_MainBuildListedUpdateLogs | String | Listed-Update-Logs/Main-Build |
| Files_PreUpdateBuildGameVersion | String | Game-Version/Pre-Update-Build |
| Files_PreUpdateBuildListedUpdateLogs | String | Listed-Update-Logs/Pre-Update-Build |
| Files_UpdateLogsURLStart | String | https://bobdevstudio.github.io/RBAP-Wiki/Posts/Update-Log |
| FlagsSystem_UpdateCheckTime | Number | 300 |
| Game_IsDevBuild | Bool | false |
| Game_IsImagingBuild | Bool | false |
| Game_IsMainBuild | Bool | true |
| Game_IsPreUpdateBuild | Bool | false |
| GameRooms_Game | Number | 24 |
| GameRooms_ImprovedLightChaserEnabled | Bool | false |
| GameRooms_LightChaserInfoRewriting | Bool | false |
| GameRooms_StartDelay | Number | 15 |
| Intro_QuietAnimateScript | Bool | false |
| NameTag_TitlePreferencePlaceKeep | Bool | true |
| NewDocks_NotNewCheckStop | Bool | true |
| NewDocks_NotNewTime | Number | 1635966000 |
| Season_LockInSummer | Bool | false |
| ServerInfo_RunTimeDisplayExactSeconds | Bool | false |
| ServerInfo_RunTimeDisplaySeconds | Bool | false |
| StreetLights_DebugColorEnabled | Bool | false |
| Time_SecondTrackingEnabled | Bool | false |
| TimeGameTime_DayTrackingEnabled | Bool | false |
| TimeGameTime_HourTrackingEnabled | Bool | false |
| TimeGameTime_MinuteTrackingEnabled | Bool | true |
| TimeGameTime_MonthTrackingEnabled | Bool | false |
| TimeUTC_DayTrackingEnabled | Bool | false |
| TimeUTC_HourTrackingEnabled | Bool | false |
| TimeUTC_MinuteTrackingEnabled | Bool | true |
| TimeUTC_MonthTrackingEnabled | Bool | false |
| TimeZone_Difference | Number | -8 |
| TopbarPlus_DisableUselessOutputs | Bool | true |
| UpdateLogs_TitleClass | String | page-title non-splash-page-title |
| UpdateLogs_TitleId | String | page-title |

### Type Key:

* `Bool` - A value of true or false.
* `String` - Just a normal string with nothing special about how the flags system uses it.
* `Number`
* `Color` - A string encoded so it tells the flag system that its value should be a color. The bot automatically transfers it into the `rgb(Red, Green, Blue)` format for easy reading.
* `(Remove Code) String` - A string that is the same as the remove code which tells the flag system when an overwrite file is used that flag should not exist.
* `Table` - A list of values optionally defined by keys.