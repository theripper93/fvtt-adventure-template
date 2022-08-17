## Setting up the Adventure

### Chose an ID

The adventure id will be needed in multiple spots, once you have chosen the id (eg `lost-mines-3d`) contact me on discord and i'll create a clone of this repository with the aropriate data setup with the id chosen.

### Clone this repository

Once the repository for your adventure is ready, you'll need to clone it from gihub. It's suggested to use VS CODE for ease of use. Once you cloned the repository, select your foundry modules folder as the target of the clone. If all went well, after restarting Foundry, you should see the Adventure Template in your modules list.

### Setting up the manifest.json

In VSCODE (or other editor) select the manifest.json file. We are gonna use examples as if we were setting up the "Lost Mines" adventure.

Change `"title": "Adventure Template",` with `"title": "Lost Mines: a 3D Adventure",`

Change `"description": "This is a short description of the adventure! Meant to be played with 3D Canvas.",` to `"description": "Delve into the Lost Mines to uncover ancient secrets and forgotten artifacts. Meant to be played with 3D Canvas.",`

Under `"authors"` fill in the sample author filed with your information.

Under `"packs"` change `"label": "Adventure Template",` to `"label": "Lost Mines: a 3D Adventure",`

### Making the adventure

Now that the module is setup, create a new world with 3D Canvas and the adventure module enabled.

Create all the required scenes, notes, actors etc...

ANY asset that is not included in the `3D Canvas Mapmaking Pack` or `3D Token Collection` must be placed inside the `assets` folder located in the same folder as the manifest.json file

Once you have a suitable image, replace the `banner.png` file in the `assets` folder with an image representative of the adventure

### Packaging the adventure.

Once the adventure is done, head to the compendiums tab in foundry and locate the adventure compendium. (You might need to right click -> unlock to enable editing)

Click on the adventure compendium to open it and on the bottom click on "Create Adventure"

Fill out the form and select your banner image

You are done! You can now send your adventure as a PR to the repository and i'll procede to publish it!

