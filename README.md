# get_bus_info
Download bus line from the Internet

This repo show you how to download bus line and bus station based on map providers (such as amap, in this case). They can be used for bus operation analysis and many potential applications.

**Step 1**: Open the map website and the "Developer Mode" (Chrome recommended)

**Step 2**: Switch to `Network/All/Preview`,  then search for your expected bus line 

![image-20201031193024761](/Users/yj/Nutstore Files/我的坚果云/900 My_Code/get_bus_info/image/image-20201031193024761.png)

**Step 3**: Click the first item, then you will see the information under the keyword `data`. 

**Step 4**: Copy the information and paste it into your local scripts (See `shanghai_bus_line.py` for example) 

![image-20201031193319368](/Users/yj/Nutstore Files/我的坚果云/900 My_Code/get_bus_info/image/image-20201031193319368.png)

**Step 5**: Get the bus line information and bus station information (See `get_bus_geo_info_manually.ipynb`)

**Note**:

1. Geopandas package is required.
2. The GPS coordinator converter is copied from [知名博主小旭学长](https://gitee.com/ni1o1/CoordinatesConverter)
3. This repo is used for academic purpose only, do not be a bad boy.

