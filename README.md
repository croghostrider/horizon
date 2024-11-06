
# Horizon
I would like to conduct a horizon survey for a window.

My idea is to take two photos – one from each of the left and right bottom corners of the window looking outward – using a 200° camera.

From these images, the horizon should be calculated.
Here is an example of the photos:
|left|right|
|--|--|
|![window corner left](https://github.com/croghostrider/horizon/blob/main/image/sampel/window%20corner%20left.jpg?raw=true)|![window corner right](https://github.com/croghostrider/horizon/blob/main/image/sampel/window%20corner%20right.jpg?raw=true)  |

The horizon should be measured from these pictures, here is an example, it is not exact:
![measurement](https://github.com/croghostrider/horizon/blob/main/image/sampel/window%20corner%20left%20-%20measurement.jpg?raw=true)
I need the measurement as a CSV file, here the structure for the CSV file:
|# |Azimuth |Elevation |
|--|--|--|
| 1 |-10|60|
| 2 |20|55|
| 3 |20|45|
| 4 |80|30|

# the project requirements:

 - Created in Python
 - Generation and storage of the 200° camera's calibration data using a ChArUco board
 - Evaluation of the quality of the calibration images
 - Manual marking of the horizon in the image (maximum 180° azimuth)
 - Calculation of the horizon based on the marking
 - Export of the horizon measurement as CSV

# Optional:

 - Automatic horizon detection in the image, with the option for manual correction

you can find the calibration pictures [here](https://github.com/croghostrider/horizon/tree/main/image/calibration).

