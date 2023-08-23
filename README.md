# Unity Project Template

This is a project template for Unity 2021-3.15f1 or later, ready to go together with git. Additionally, to deal with the license hassles with the Unity Asset Store's assets (like, bought assets are NOT to be distributed, of course...).

## Setup

   
1. Rename the folder "Sample-Project" in the assets
2. **IMPORTANT:** Edit .gitignore, line 11. Replace "Sample-Project" to this folder's new name, too.
3. Start Unity, to update the .meta files, too.
4. Optional: Edit the AssetStoreLoader.cs to update its Asset Store shopping list (the asset store items which you want to be included).
5. In the next update, the Loader either...
   1. includes the Asset Store item if it was already downloaded on your computer, or
   2. starts up your favourite browser to load the required Asset Store pages, to claim your required Asset Store items, or if neccessary, buy it.
6. Once finished, exit Unity **first**, **then** commit the changes.

## Reminder

1. The Assets/ root folder is **NOT** covered by git, bacause Unity and its packages is likely to heap samples, template files and so on and clutter your projects. If you really need the auto-generated files in Assets/, move into the folder you renamed to in step #1.