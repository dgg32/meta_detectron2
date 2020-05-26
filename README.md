# meta_detectron2

In this project, I try to use Facebook Detectron2 to process photos and save both the list of detected object and the photo metadata in a database. So it is possible later to search with an object and get the photos with that object. Occassionally, it can even plot their locations in the world map.


Facebook's Detectron2 can recognize the objects inside a photo:

![example](https://github.com/dgg32/meta_detectron2/blob/master/IMG_1743.jpeg_detectroned.jpeg)

For example, in the example folders, I can search for "cat" and then plot the positive photos:

![cat_search](https://github.com/dgg32/meta_detectron2/blob/master/Screenshot%20from%202020-05-27%2000-27-12.png)
