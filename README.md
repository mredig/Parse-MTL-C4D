# Parse_MTL.py
##### Version 1.1.3

## Usage

1. Open Cinema 4D. 
2. Under the script menu, there's an option to open the script folder. Use that. 
3. Place Parse_MTL.py in that folder. 
4. You will probably need to restart C4D, but afterwards, goto "Script -> User Scripts -> Import .mtl file..."
5. Select the mtl file you wish to import.
6. The script will import the materials from the file.

## Credits

This is NOT my script. I merely edited a couple lines to turn off the specular channel if the settings in the mtl were 0 for specularity and to link to absolute values for paths. The original script is found at http://www.c4d-jack.de/site/

### ToDos

I'd like to add a toggle to change between absolute paths and relative paths.