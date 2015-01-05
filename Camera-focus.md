This [ROS](www.ros.org) node assists you with setting the focus of a camera in a reproducible way. The tool subscribes to the camera's image  topic and displays the live image together with a measure of focus. Point the camera at a scene with high frequency components (e.g. Siemens star, checkerboard) and adjust the focus while trying to minimize the calculated focus measure.

The tool can be launched with:
> kalibr_camera_focus --topic [IMAGE_TOPIC]


## References
Please cite the appropriate papers when using this toolbox or parts of it in an academic publication.

1. <a name="focus"></a> Matej Kristan, Franjo Pernu. Entropy Based Measure of Camera Focus.  University of Ljubljana. Slovenia.






