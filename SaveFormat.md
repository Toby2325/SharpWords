## Save File Format ##

This is the format for SharpWords' save files.
Each section of the save file will be seperated with a semicolon (;)

- Title (String. Example: "Minecraft")
- Grid Dimensions (W:H)
- Grid Bitmap (A bitmap layout of the grid in numbers which will show what cells are used and which arent. 0 = Unused, 1 = Used
- Numbered Cell Coordinates (The coordinates for the begininning of each word, followed by the direction (0 = Horizontal/Across, 1 = Vertical/Down))
- Across Words and Clues (The across words and their clues (Num=Word:Clue)
- Down Words and Clues (The down words and their clues (Num=Word:Clue)

