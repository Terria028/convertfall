# Convert Fall
Convert Fall is a conversion for Towerfall including Texture Atlas `.xml` to be converted as `.json` to be used for texture split in Texture Packer
and tower workshop(work in progress) to convert into a quest `.oel` file.

##WARNING: THIS APPLICATION IS NOT TESTED TO BE USED YET. USE AT YOUR OWN RISK, BACKUP FIRST!

# How to Use?
With the convertfall executable, you can use a command with it using the terminal or cmd. Use `-help` to see any available command.
```
convertfall.exe -help
```

**To convert a texture atlas to .json**
Use the texture command:
```
convertfall.exe texture --input "path/to/xml" --output "path/for/json" 
```
To use the `.json` file, you need to go to this website and use the app (or download the app if you want):
https://free-tex-packer.com/app/
Click on the "Split Sheet" button and put a `.png` texture on the Texture form and `.json` to Data File form and click Split. (WARNING: For user who download the app, this will split a textures without an archive. Please put it in an empty directory)

Congratulations! You may now use and extend the atlases, and export it again to `.xml` file if you are done. (Some work needed to be done of course, by replacing the text to be able to make it valid Towerfall `.xml` file)


# TODO:
- [x] Convert an atlas file to `.json`

- [ ] Convert an `.xml` file generated by Texture Packer to valid Towerfall `.xml` atlas file

- [ ] Convert a `.tower` file to `.oel`(s) file

- [ ] Convert a `.tower` file to `.json`(s) file for OGMO Editor
