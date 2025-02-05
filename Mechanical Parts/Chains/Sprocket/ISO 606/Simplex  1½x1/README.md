# Chain Sprockets ISO606 simplex 1 1/2" x 1" from z 8 to z 57

This folder contains the 3D models of the sprockets for ISO 606 chains simplex 1 1/2" x 1" with number of teeth ranging from z=8 to z=57.

![Image](../images/simplex_screenshot.png "Sprocket Simplex")

The model is parametric and the values are contained in the spreadsheet `Data`.

The parameters refer to the sprocket dimensions as in the drawing below:

![Drawing](../images/simplex_drawing.png "Drawing")

### Table of dimensions in millimeters:

P (Pitch)|Wc (Chain width)|Dr (Roller diameter)|Tr (Tooth radius)|Rw (Radius width)|Wt (Tooth width)|z (Number of teeth)|De (External Diameter)|Dp (pitch diameter)|d (Hub diameter)|D (Hole diameter)|H (Total height)
---|---|---|---|---|---|---|---|---|---|---|---
38,1|25,04|25,4|38|4|24,1|8|115|99,55|58|20|45
38,1|25,04|25,4|38|4|24,1|9|126,4|111,4|70|20|45
38,1|25,04|25,4|38|4|24,1|10|138|123,29|80|20|45
38,1|25,04|25,4|38|4|24,1|11|150|135,21|90|25|50
38,1|25,04|25,4|38|4|24,1|12|162|147,22|102|25|50
38,1|25,04|25,4|38|4|24,1|13|174,2|159,18|114|25|50
38,1|25,04|25,4|38|4|24,1|14|186,2|171,22|128|25|50
38,1|25,04|25,4|38|4|24,1|15|198,2|183,26|140|25|50
38,1|25,04|25,4|38|4|24,1|16|210,3|195,3|140|25|55
38,1|25,04|25,4|38|4|24,1|17|222,3|207,34|140|25|55
38,1|25,04|25,4|38|4|24,1|18|234,3|219,42|140|25|55
38,1|25,04|25,4|38|4|24,1|19|246,5|231,49|140|25|55
38,1|25,04|25,4|38|4|24,1|20|258,6|243,57|140|25|55
38,1|25,04|25,4|38|4|24,1|21|270,6|255,65|150|25|60
38,1|25,04|25,4|38|4|24,1|22|282,7|267,73|150|25|60
38,1|25,04|25,4|38|4|24,1|23|294,8|279,8|150|25|60
38,1|25,04|25,4|38|4|24,1|24|306,8|291,88|150|25|60
38,1|25,04|25,4|38|4|24,1|25|319|304|150|25|60
38,1|25,04|25,4|38|4|24,1|26|331|316,08|160|30|60
38,1|25,04|25,4|38|4|24,1|27|343,2|328,19|160|30|60
38,1|25,04|25,4|38|4|24,1|28|355,2|340,27|160|30|60
38,1|25,04|25,4|38|4|24,1|29|367,3|352,38|160|30|60
38,1|25,04|25,4|38|4|24,1|30|379,5|364,5|160|30|60
38,1|25,04|25,4|38|4|24,1|31|391,6|376,62|160|30|60
38,1|25,04|25,4|38|4|24,1|32|403,7|388,69|160|30|60
38,1|25,04|25,4|38|4|24,1|33|415,8|400,81|160|30|60
38,1|25,04|25,4|38|4|24,1|34|427,8|412,93|160|30|60
38,1|25,04|25,4|38|4|24,1|35|440|425,04|160|30|60
38,1|25,04|25,4|38|4|24,1|36|452|437,16|160|30|60
38,1|25,04|25,4|38|4|24,1|37|464,2|449,27|160|30|60
38,1|25,04|25,4|38|4|24,1|38|476,2|461,39|160|30|60
38,1|25,04|25,4|38|4|24,1|39|488,5|473,5|160|30|60
38,1|25,04|25,4|38|4|24,1|40|500,6|485,62|160|30|60
38,1|25,04|25,4|38|4|24,1|45|561,2|546,19|160|30|90
38,1|25,04|25,4|38|4|24,1|50|621,7|606,78|160|30|90
38,1|25,04|25,4|38|4|24,1|57|706,5|691,63|170|30|100

The 3D model configuration of each sprocket can be dynamically retrieved using a preset `Configuration table`.
The file name of the 3D model containing the `Configuration table` is **`Sprocket ANSI simplex 1½x1.FCStd`**.

To obtain the 3D model of the desidered sprocket, click the spreadsheet `Data` in the Tree View and then select the `Teeth Number` in the property editor. If nothing changes try to `Refresh` the model.

See the following image for details

![Drawing](../images/configuration.png "Configuration")

### Notes for developers
If you add a row in the `Configuration table` of the `Data` spreadsheet, then add that row in the above table of this `README.md` file, without the first cell.
