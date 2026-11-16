# LaunchCtrl quick setup

## Installation tab

This copy starts with three visible tiles: StepMania, ITGmania and Project
OutFox. Installation paths start blank. Settings are saved in `settings.xml`
beside `LaunchCtrl.exe`, separately from other launcher copies. Share a fresh
copy without `settings.xml` for new users.

Select the game installation root—the folder containing its `Program` folder.
You can also select the `Program` folder or enter the game's executable. Do
not select `Preferences.ini`, `Save`, or `Songs`.

- **StepMania:** folder containing `Program\StepMania.exe` (modern StepMania 5 only)
- **ITGmania:** folder containing `Program\ITGmania.exe`
- **Project OutFox:** folder containing `Program\OutFox.exe`

Click **Load / refresh**. Check the displayed **Preferences** path before
applying presets. Start the game once first if it has not created preferences.

StepMania's Preset controls show themes in a scrollable list. Select a theme,
then use **Apply** or **Apply and launch** to use it.

If `Portable.ini` is in the installation root, preferences are at
`<installation root>\Save\Preferences.ini`. Otherwise, they are under
`%APPDATA%`:

- StepMania: `StepMania 5.1\Save\Preferences.ini` or `StepMania 5\Save\Preferences.ini`
- ITGmania: `ITGmania\Save\Preferences.ini`
- Project OutFox: `Project OutFox\Save\Preferences.ini` or `OutFox 5.3\Save\Preferences.ini`

## Tile images

Put PNG images in the `Tile Images` folder beside `LaunchCtrl.exe`. In
**Settings > Tiles**, choose an image in the tile's **Tile image** field and
save. Adding an image makes it available but does not assign it automatically.

## Song packs

Active songs are in `Songs`; stored packs go in `SongPacks` beside it. In
**Settings > Installation**, click **Set up SongPacks** to create the empty
folder. Copy each pack into its own folder there. Folders in `Songs` and
`SongPacks` appear as **Song pack** choices after refresh.

Choose a pack for a tile and save. Saving stores the selection; songs move
only when you apply or launch that tile. LaunchCtrl moves other folders from
`Songs` into `SongPacks`, then moves the selected pack into `Songs`.
Selecting `-none-` leaves the current `Songs` folder unchanged. Close the
game before applying a preset, and keep a backup of the song library.
