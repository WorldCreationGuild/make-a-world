# [Go to Wiki](../../wiki)

# How to Use GitHub to manage files

So GitHub uses Git to manage files and file history, but you don't have to know how to use Git when you're using GitHub's web interface! It's best to use a desktop computer, but the web interface on your phone will also work!

## Creating & Changing Files in the Project

Whenever you want to add a new file, just click that nifty "Add file" button and you can either [create a new text file](https://github.com/WorldCreationGuild/make-a-world/new/main) or [upload any file](https://github.com/WorldCreationGuild/make-a-world/upload/main), like an image or something. (If you do add images and non-text files, please try to keep them small in file size. GitHub doesn't usually care, but it's like a courtesy thing.) If you upload a file with the same exact name as another, it will overwrite the previous file, but the previous version of the file will still exist in the project's [history](https://github.com/WorldCreationGuild/make-a-world/commits/main). You can also edit existing text files by clicking the pencil icon in the top right corner that appears when you click the name from the project's [Code screen](https://github.com/WorldCreationGuild/make-a-world).

Each time you upload or create a file, there's a set of fields at the bottom of the screen labeled "Commit changes" where you can write about why you're adding or changing the file. The first line is a summary of what is added or changed (like "Fixed some typos") and the second text area is to go into more detail. This is optional, but if you do change something it would be good to use these fields so we can keep track of things. Whether you add a message or not, keep the default settings below and click the green "Commit changes" button to save.

If you upload a file and want it to be moved to a specific folder for better organization, either let Robbie know or create an [Issue](../../issues) with a link to the file and the folder you want it to be in and he'll move it. Also be sure to include any wiki pages where you have linked to the file so the links can be updated, if relevant.

## Using the GitHub Wiki

The wiki is linked at the top of this document and should be used to store all the text for the world formatted in [Markdown](https://guides.github.com/features/mastering-markdown/). Any text files in the project itself (i.e. added via the method above) should be reserved for code like tools and stuff and _not_ for information about whatever world we are making.

If you ware a member of the team or otherwise have permissions to edit the wiki, you should see "Edit" and "New Page" buttons in the top right corner of the wiki page. This should be fairly self-explanatory, plus there's a handy "Preview changes" tab on the text editor that can help you make sure your Markdown looks correct before saving. New and edited wiki pages also have an "Edit message" field, which is like the "Commit changes" fields mentioned above but it's shorter. Be sure to write something in there when making non-trivial changes.

You can link to other pages or implicitly create links to nonexistent wiki pages by using Mediawiki format `[[Name of Wiki page]]` or if you don't want to use the name of the page as the text, you can just use regular `[Markdown links](../Page%20Name)`, but that can get complicated if you're not careful. Linking to a non-existent wiki page will start a "New Page" creation process so you can make it exist after you're done working on the current page.

Finally, after uploading files from the "Add file" button, you can link to them using `[Markdown links](link/to/file)`. If you want an image to _display_ on the page instead of just linking to it, open the file from the project view, get the actual image URL by right-clicking it and choosing "Copy Image Location/Address" and using the `![Markdown image link format](link/to/image)` (the same as a regular link but with an exclamation point at the beginning).

# Conclusion

That should be everything. Let Robbie know if he missed something and he'll help you out!
