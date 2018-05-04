# Autotool
Bulk do something in Sketch like bulk change text everywhere

## Disclaimer!
It's in very early stage, it might break your document!
Also it's very poorly written . . .

## What does it do?
It allows you to automatically do some bulk operations in Sketch like:

### Quickly manage the copy in your design
1. Find "some_text" (both withing a text layer or a symbol) and replace it with "some_other_text"
2. Export all the texts found in a page (both symbols and text layers) to a JSON
3. Import the JSON as per above (once a tech/copy writer has reviewed and/or modified the text inside)

### Rename the selected layers
4. Select a bunch of layers and rename those layers like WHATEVER 01, WHATEVER 02, WHATEVER 03, WHATEVER XX . . . 
5. Select a bunch of layers and replace part of the name of those layers
6. Select a bunch of layers and add a prefix to all of them
7. Select a bunch of layers and add a suffix to all of them
8. Select a bunch of layers and rename all of them the same

### Automatically select layers
9. Select 1 symbol > run plugin, and it will select the same symbol everywhere in your page
10. Select 1 text layer > run plugin, and it will select all the text layers that have the same text inside

### Change color to selection
11. Select some layers (only text and shapes) and apply a custom color
12. Select some layers (only text and shapes) and apply black color
13. Select some layers (only text and shapes) and apply white color

### Add a slice to all your exportable
14. Duplicate your document and add slices to all your exportable symbols and breaks all your symbols
15. Add slices to all your exportable symbols

#### Updated to work with Sketch 49.3
