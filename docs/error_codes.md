I realise that error codes can get frustrating, especially since you are trying to make the best game on Roblox ;) so I made a quick table for you! All the severity levels & types are listed and you can easily see the error code & try and fix it! You can also contact me, @phoenixthedev_, on Discord so I can further assist you depending on what it is.

I also have some quick tips for you for you to take action based on severity!

- Low, If anything has a severity level of low, it means that the player won't be affected in gameplay, however if you notice it is happening in a large scale, you may want to investigate further to see if it is truly impacting user experience.

- Medium, The player might be affected, but will be a minor impact e.g Button Animation not working

- High, The player's gameplay experience will be impacted, this is where you should start investigating ASAP if players are getting the issue.

- Critical, The player's gameplay will be heavily impacted, e.g a Plot will not be able to function or their data was wiped. 

My advice? Anything above High prioritise the most, and anything medium or low, only investigate if it's happening at a large scale. **But you should always investigate if you have time, the advice given is just a hierarchy of importance.**

If anything has a severity level of low, it means that the player won't be affected in gameplay, anyhow, here's the table!

| Code | Type | Personal Message | Severity |
|------|------|------------------|----------|
| **B301** | Button | An error occurred whilst getting the data Button Purchase, this may be due to an error whilst initializing ComplieButtonDataService or the user is attempting a DoS attack (Exploiter). Check console / Error Report for more information. | High - Low |
| **B302** | Button | An error occurred whilst getting the data Button Purchase, this may be due to an error whilst initializing ComplieButtonDataService as some data (ButtonName) is missing. | High |
| **B303** | Button | An error occurred whilst getting the data for Button Purchase, this may be due to an error whilst initializing ComplieButtonDataService as some data (Price) is missing. | High |
| **B304** | Button | An error occurred during Button Purchase, the Data was mismatched? This may be due to an error whilst initializing ComplieButtonDataService as some data (ButtonName) is mismatched but most likely an exploiter. | High - Low |
| **B305** | Button | An error occurred during Button Purchase, the Data was mismatched? This may be due to an error whilst initializing ComplieButtonDataService as some data (Price) is mismatched but most likely an exploiter. | High - Low |
| **B506** | Button | *RARE* An error occurred during Button Purchase, Rare Error, this is likely due to exploiters or server bug, resorting to backup. | Low |
| **B607** | Button | An error occurred during Button Purchase, Expected Error, player doesn't own any plots. | Low |
| **B608** | Button | An error occurred during Button Purchase, expected error // rare, the button event was fired twice & the player already has the asset in their plot. | Low |
| **D901** | DataStore | An error occurred during DataStore (GET), this may be an internal server error, Check Creator Dashboard -> Monitoring -> Data Stores -> Request Count by API x Status and select ALL for the second parameter & SetAsync for the first. A warning or error will also be logged in Error Report / Console with more info. | Critical |
| **D902** | DataStore | An error occurred during DataStore (SET), this may be an internal server error, Check Creator Dashboard -> Monitoring -> Data Stores -> Request Count by API x Status and select ALL for the second parameter & GetAsync for the first. A warning or error will also be logged in Error Report / Console with more info. | Critical |
| **D903** | DataStore | An error occurred during DataStore (UPDATE), this may be an internal server error, Check Creator Dashboard -> Monitoring -> Data Stores -> Request Count by API x Status and select ALL for the second parameter & UpdateAsync for the first. A warning or error will also be logged in Error Report / Console with more info. | Critical |
| **P501** | Plot | Unknown error whilst creating plot, player already owns plot. | Low |
| **P502** | Plot | Unknown error whilst clearing plot, no player assigned to this plot previously. | Low |
| **P103** | Plot | There isn't a PlotAssetsFolder located under the plot? | Critical |
| **P704** | Plot | There isn't a Buttons Folder located under the plot? | Critical |
| **P105** | Plot | There isn't a ClaimPlot Folder or there isn't any supported instance (ProximityPrompt under a part called "ProximityPart" or a Part named "TouchPart"). | Critical |
| **A101** | Attribute | You haven't made an attribute called "WhichGearToGive" or there's no value inside the attribute. | High |
| **A102** | Attribute | You haven't added a tool under ServerStorage -> Framework -> CoreAssets -> Gear that corresponds with the WhichGearToGive attribute on the Gear Box. | High |
| **A103** | Attribute | There isn't any supported instance (ProximityPrompt under a part called "ProximityPart" or a Part named "TouchPart") on the gear box. | High |
| **A104** | Attribute | There isn't a hitbox part. - Owner Only Door. | High |
| **A105** | Attribute | There isn't a part labelled ButtonPart and has a click detector as a child. - Owner Only Door. | High |