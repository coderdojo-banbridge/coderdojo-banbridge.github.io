### Mission Space Lab

| Project Teams | *Team Terra Marique* | *Lux Quest* |
| --- | --- | --- |
| Idea          | Land and Sea Detector to build up a model of visible area from the ISS | Light pollution Detector to determine areas of high light pollution |
| How does it use the Astro Pi to perform the experiment? | It will use the Pi NoIR camera to capture images of the Earth and post-process to detect variations in light intensity to determine land or sea and then possibly model the results in MineCraft on the Pi or else on the Sense Hat LED display. | It will use the Pi NoIR camera to capture images when ISS is over land in darkness. It will post process the images and determine biggest offenders of light pollution. The results may be displayed in a minecraft model and also displayed on the Sense Hat LED display. |
| Phase 1 feedback | Nice idea, remember that you'll get 3 hours of run time for your code which is 2 orbits. So not enough to get full global coverage for your Minecraft map. | Look into using two-line element telemetry to calculate ISS location. The Python ephem module is perfect for this. You can also work out if you're on the light or dark side of the Earth. |

### Further Resources

| Resource                                                                                   | Details                                                                                                |
|--------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| [Learn Python](python.md)                                                                  | Learn Python                                                                                           |
| [Photos from ISS](https://github.com/astro-pi/enviro-pi/tree/master/iss%20downloads)       | Examples of images taken from ISS on last set of space missions                                        |
| [Two-line element set](https://en.wikipedia.org/wiki/Two-line_element_set)                 | Article explaining two-line telemetry. |
| [PyEphem Home Page](http://rhodesmill.org/pyephem/index.html)                              | Python library that works with two-line telemtry. |
| [NORAD Two-Line Telemtry](http://celestrak.com/NORAD/elements/stations.txt)                | NORAD's up to date two-line telemtry data. |
| [Raspbian Stretch: Install OpenCV 3 + Python on your Raspberry Pi](https://www.pyimagesearch.com/2017/09/04/raspbian-stretch-install-opencv-3-python-on-your-raspberry-pi/) | Great guide on how to install OpenCV on Raspberry PI (**Can take over an hour to complete!**)
| [Accessing the Raspberry Pi Camera with OpenCV and Python](https://www.pyimagesearch.com/2015/03/30/accessing-the-raspberry-pi-camera-with-opencv-and-python/) | Great guide on how to capture images using OpenCV on the Raspberry PI. |
