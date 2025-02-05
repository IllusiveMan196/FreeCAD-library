# Chain Plate Wheels ISO606 simplex 1" x 17,02 from z 8 to z 30

This folder contains the 3D models of the plate wheels for ISO 606 chains simplex 1" x 17,02 with number of teeth ranging from z=8 to z=30.

![Image](../images/simplex_screenshot.png "Plate Wheel Simplex")

The model is parametric and the values are contained in the spreadsheet `Data`.

The parameters refer to the plate wheel dimensions as in the drawing below:

![Drawing](../images/simplex_drawing.png "Drawing")

### Table of dimensions in millimeters:

P (Pitch)|Wc (Chain width)|Dr (Roller diameter)|Tr (Tooth radius)|Rw (Radius width)|Wt (Tooth width)|z (Number of teeth)|De (External Diameter)|Dp (Pitch diameter)|D (Hole diameter)|H (Total height)
---|---|---|---|---|---|---|---|---|---|---
25,4|17,02|15,88|26|2,5|16,2|8|77|66,37|12|16,2
25,4|17,02|15,88|26|2,5|16,2|9|85|74,27|12|16,2
25,4|17,02|15,88|26|2,5|16,2|10|93|82,19|12|16,2
25,4|17,02|15,88|26|2,5|16,2|11|101,5|90,14|16|16,2
25,4|17,02|15,88|26|2,5|16,2|12|109|98,14|16|16,2
25,4|17,02|15,88|26|2,5|16,2|13|117|106,12|16|16,2
25,4|17,02|15,88|26|2,5|16,2|14|125|114,15|16|16,2
25,4|17,02|15,88|26|2,5|16,2|15|133|122,17|16|16,2
25,4|17,02|15,88|26|2,5|16,2|16|141|130,2|20|16,2
25,4|17,02|15,88|26|2,5|16,2|17|149|138,22|20|16,2
25,4|17,02|15,88|26|2,5|16,2|18|157|146,28|20|16,2
25,4|17,02|15,88|26|2,5|16,2|19|165,2|154,33|20|16,2
25,4|17,02|15,88|26|2,5|16,2|20|173,2|162,38|20|16,2
25,4|17,02|15,88|26|2,5|16,2|21|181,2|170,43|20|16,2
25,4|17,02|15,88|26|2,5|16,2|22|189,3|178,48|20|16,2
25,4|17,02|15,88|26|2,5|16,2|23|197,5|186,53|20|16,2
25,4|17,02|15,88|26|2,5|16,2|24|205,5|194,59|20|16,2
25,4|17,02|15,88|26|2,5|16,2|25|213,5|202,66|20|16,2
25,4|17,02|15,88|26|2,5|16,2|26|221,6|210,72|20|16,2
25,4|17,02|15,88|26|2,5|16,2|27|229,6|218,79|20|16,2
25,4|17,02|15,88|26|2,5|16,2|28|237,7|226,85|20|16,2
25,4|17,02|15,88|26|2,5|16,2|29|245,8|234,92|20|16,2
25,4|17,02|15,88|26|2,5|16,2|30|254|243|20|16,2

The 3D model configuration of each plate wheel can be dynamically retrieved using a preset `Configuration table`.
The file name of the 3D model containing the `Configuration table` is **`Plate Wheel simplex 1" x 17,02.FCStd`**.

To obtain the 3D model of the desidered plate wheel, click the spreadsheet `Data` in the Tree View and then select the `Teeth Number` in the property editor. If nothing changes try to `Refresh` the model.

See the following image for details

![Drawing](../images/configuration.png "Configuration")

### Notes for developers
If you add a row in the `Configuration table` of the `Data` spreadsheet, then add that row in the above table of this `README.md` file, without the first cell.
