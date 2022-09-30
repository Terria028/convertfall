# Convert Fall
Convert Fall is a conversion for Towerfall including textures to be converted as `.json` to be used for texture split and tower workshop(work in progress) to convert 
into a quest `.oel` file.

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


# TODO:
- [x] Convert an atlas file to `.json`

- [ ] Convert an xml file generated by Texture Packer to valid Towerfall xml atlas file

- [ ] Convert a `.tower` file to `.oel`(s) file

- [ ] Convert a `.tower` file to `.json`(s) file for OGMO Editor
