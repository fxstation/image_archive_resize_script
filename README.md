# image_archive_resize_script
Batch image convertion in zip files with infranview and 7-zip 

Infranview has a very powerful feature of batch converting images and I use it a lot to shrink the images in a zip file.

However, the operation is not very effective, where I have to:
1. Inspect if the zip file is big enough which needed to be shrinked.
2. unzip the content.
3. use Infranview to convert the images
4. zip the converted images
5. replace the original zip

My goal is to automamte the process, so that I can have an item on context menu to do all the above step in 1-click on the zip file.

Additionally, an analysis of the zip file before the conversion is nice to have feature. 
It could show the average size of files, number of files in the zip and the file type.

If all these works, I may create an explorer to batch convert all zip files within a folder. In there I can select the zip files to work on by providing custom filters.

At the moment, I may use power shell or python to implement this.
