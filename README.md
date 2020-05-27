# meta_detectron2

In this project, I try to use Facebook Detectron2 to process photos and save both the list of detected object and the photo metadata in a database. So it is possible later to search with an object and get the photos with that object. In addition, this notebook can even plot the selected photo locations in the world map.

This function is also seen in Apple's closed source Photos.app. But in Photos.app, the detections seem a touch and go thing, i.e. it select many wrong photos. Also it keeps recognition outputs hidden from our prying eyes.


Facebook's Detectron2 can recognize the objects inside a photo:

![example](https://github.com/dgg32/meta_detectron2/blob/master/IMG_1743.jpeg_detectroned.jpeg)

For example, in the example folders, I can search for "cat" and then plot the positive photos:

![cat_search](https://github.com/dgg32/meta_detectron2/blob/master/Screenshot%20from%202020-05-27%2000-27-12.png)


## Authors

* **Sixing Huang** - *Concept & Coding*

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* ![Extract lat lon from Exif](https://developer.here.com/blog/getting-started-with-geocoding-exif-image-metadata-in-python3).
* ![Detectron2](https://github.com/facebookresearch/detectron2)
* ![Folium](https://python-visualization.github.io/folium/quickstart.html)
