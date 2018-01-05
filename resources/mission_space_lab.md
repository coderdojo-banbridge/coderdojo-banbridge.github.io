### Mission Space Lab

#### About

In October 2017, two teams of Ninja's submitted projects ideas for the ESA [Astrp PI - Mission Space Lab](https://astro-pi.org/missions/space-lab/) competiton for young people no older than 19. They submitted ideas for an experiment, and both were accepted which means that our Dojo received free computer hardware that mirrors that in Space. Now the hard part, they must write the Python code to carry out those ideas!

If successful, their code could be uploaded to the International Space Station and run for three hours (two orbits).

Out of the two themes (Life on Earth or Life in Space) both teams submitted ideas for **Life in Space** which makes use of Astro Pi IR (Izzy), which will be aimed towards the Earth through a window. They can use all of its sensors as well as its infrared camera.

#### Project Details

| Project Teams | *Team Terra Marique* | *Lux Quest* |
| --- | --- | --- |
| Idea          | Land and Sea Detector to build up a model of visible area from the ISS | Light pollution Detector to determine areas of high light pollution |
| How does it use the Astro Pi to perform the experiment? | It will use the Pi NoIR camera to capture images of the Earth and post-process to detect variations in light intensity to determine land or sea and then possibly model the results in MineCraft on the Pi or else on the Sense Hat LED display. | It will use the Pi NoIR camera to capture images when ISS is over land in darkness. It will post process the images and determine biggest offenders of light pollution. The results may be displayed in a minecraft model and also displayed on the Sense Hat LED display. |
| Phase 1 feedback | Nice idea, remember that you'll get 3 hours of run time for your code which is 2 orbits. So not enough to get full global coverage for your Minecraft map. | Look into using two-line element telemetry to calculate ISS location. The Python ephem module is perfect for this. You can also work out if you're on the light or dark side of the Earth. |

#### Approach

Some tips were shared during a [recent webinar](https://astro-pi.org/updates/mission-space-lab-training-webinar/) hosted by the astro pi team that should aid with tackling the projects:
* For Life On Earth projects, images can be captured and stored to be processed by another program at a later point. This means that intensive processing of images can actually be tackled later which is important as the Pi on the space station is one of the older models and may not complete each image processing in a timely fashion.
* Because of the point above, we can break the projects into seperate parts/programs that can be tackled by the seperate ninja's and pull it together at the end, e.g. one ninja can write the code to take photos and note location using ephem and store details in a csv (comma seperated value) file, while another could write the code that processes the image and gathers data and another the code to represent data in Minecraft.

#### Further Resources

| Resource                                                                                   | Details                                                                                                |
|--------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| [Learn Python](python.md)                                                                  | Learn Python                                                                                           |
| [Photos from ISS](https://github.com/astro-pi/enviro-pi/tree/master/iss%20downloads)       | Examples of images taken from ISS on last set of space missions                                        |
| [Two-line element set](https://en.wikipedia.org/wiki/Two-line_element_set)                 | Article explaining two-line telemetry. |
| [PyEphem Home Page](http://rhodesmill.org/pyephem/index.html)                              | Python library that works with two-line telemtry. |
| [NORAD Two-Line Telemtry](http://celestrak.com/NORAD/elements/stations.txt)                | NORAD's up to date two-line telemtry data. |
| [Raspbian Stretch: Install OpenCV 3 + Python on your Raspberry Pi](https://www.pyimagesearch.com/2017/09/04/raspbian-stretch-install-opencv-3-python-on-your-raspberry-pi/) | Great guide on how to install OpenCV on Raspberry PI (**Can take over an hour to complete!**)
| [Accessing the Raspberry Pi Camera with OpenCV and Python](https://www.pyimagesearch.com/2015/03/30/accessing-the-raspberry-pi-camera-with-opencv-and-python/) | Great guide on how to capture images using OpenCV on the Raspberry PI. |
