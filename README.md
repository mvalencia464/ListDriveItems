# ListDriveItems
Use Apps Script to list out all items in a Google Drive folder.

USE CASE: If you need to reference lots of images in your Google Drive folder, you can easily use this script. You will end up with a spreadsheet with the filenames in one column and the unique URL for the image in another column. I used it to create thousands of images for scheduling a year's worth of social media content in a single day.

HOW TO USE IT:

1. Create a new Google Spreadsheet
2. Click on "Extensions" in the menu bar, then "Apps Script"
3. Paste the code from "Script" that you downloaded above
4. Replace 'your-folder' to the name of the folder you want to list. (i.e., 'Example Folder').
5. Click "Save"
6. Click "Run"
7. Review Permissions (Note: You'll see a warning that it's unsafe to proceed, but you're fine and can see script is fine to use, click proceed)
8. It should automatically create a new spreadsheet with the two columns and if there are images, all the unique URLs assigned by Google Drive.
9. Possible obstacles: (1) If it doesn't create a spreadsheet, try "Run" again and make sure you've reviewed permissions for each parent folder. (2) If you have to review permissions for too many files, you can set the folder to public if you'd like.

Enjoy!
