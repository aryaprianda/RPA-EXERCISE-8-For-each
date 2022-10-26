# RPA-EXERCISE-8-For-each
Perulangan For Each

1. Create a Sequence
2. Drag and Drop a Browse for Folder Activity. In the selected folder path, enter strSelectedFolder
3. Drag and Drop an assign activity
4. Create an array of strings variable named arrString. (The variable type will look like this String[] 
5. Put in the value in the expression as Directory.GetFiles(strSelectedFolder)
6. Drag and drop a For each activity. Change the value in the expression as arrString
In the Body of the For each activity, drag and drop a write line activity. Enter item.tostring
7. Run the automation.
