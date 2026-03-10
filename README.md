# Panorama

A mod for Cities: Skylines that creates panoramic screenshots by automatically rotating the camera and stitching multiple images together.

## Compatibility

This mod is compatible with the Mass Transit update.

## How It Works

- The mod rotates the camera around the Y-axis slightly, takes a screenshot, and repeats the process.
- It then joins these screenshots together to create a panoramic image.

## How to Use

1. Press `Ctrl+Alt+P` (default hotkey) to open the "Panorama Settings" panel. You can change the hotkey by editing the file `Cities_Skylines/ScreenShotP/hotkey.txt`.

2. In the settings panel, you'll find three parameters:
   - **Step**: The number of pixels the camera rotates each time. A lower value results in higher quality but increases the waiting time.
   - **Width**: The total number of degrees the camera rotates.
   - **Filename**: The base name for your screenshots. Files will be saved in the `Cities_Skylines/ScreenShotP` folder with the format `yyyyMMdd_HHmmss_[filename].png`.

3. Use the buttons:
   - **Open Folder**: Opens the folder where screenshots are saved.
   - **Start**: Begins the panoramic scan using the configured parameters.
