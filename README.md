# Crab Champions Save Manager

This tool is a custom solution designed to help you manage your game runs in Crab Champions. As the game allows only one saved run at a time, this script will let you extract, save, and load multiple runs as you need. With the functionality of the tool, you can swap out different runs without permanently overwriting your current game state. 

## Features

1. **Extract Current Run**: The script can load your game's `SaveSlot.sav` file and extract the current run data, saving it as a separate JSON file for easy access and readability.

2. **Insert Run**: You can replace the current run in the `SaveSlot.sav` file by inserting a previously saved run in JSON format.

3. **Save Game State as JSON (Optional)**: If you wish to take a closer look at the game's save file, you can opt to convert the entire `SaveSlot.sav` into a readable JSON format. This allows for manual modification of different parameters within the game's save file.

4. **Convert JSON to .sav**: After making changes to the JSON version of the game state, you can convert it back to the .sav format.

## How To Use

1. **Extract a Run**: Load your `SaveSlot.sav` file and the tool will display the current run data. If a run exists, you can choose to extract it by clicking the 'Extract' button.

2. **Insert a Run**: If you wish to load a different run, click on 'Insert' and select the desired saved run in JSON format. If no run is currently in progress, you can still insert a previously saved run.

After you insert a run, the tool will automatically download the updated `SaveSlot.sav` file to your Downloads folder. The downloaded file will be named `SaveSlot_run_name.sav`, where `run_name` corresponds to the inserted run.

> Important: Make sure to rename the downloaded file to `SaveSlot.sav` and replace the existing one in your `SaveGames` directory.

## Game Save Directory

The default directory for your game save file in Crab Champions is `%USERPROFILE%\AppData\Local\CrabChampions\Saved\SaveGames`. You need to overwrite the `SaveSlot.sav` file in this directory with the one downloaded from the tool to see the changes in your game.

## Disclaimer

Please note that this tool is intended for personal use only. Always remember to back up your original save files before making any changes. The developer of this tool is not responsible for any data loss or unintended game behavior resulting from its use.
