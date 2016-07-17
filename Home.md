Welcome to the darknet wiki!!
I want to create an question but,I forget how to do.So I just put it here.

I want compiler yolo with OpenCV but I failed.
The reason is that 
//--------------------------------------------compiler command---------------------------------------------------
gcc  -DOPENCV `pkg-config --cflags opencv`  -Wall -Wfatal-errors  -Ofast -DOPENCV -c ./src/coco_demo.c -o obj/coco_demo.o
In file included from /usr/local/include/opencv2/highgui.hpp:46:0,
                 from /usr/local/include/opencv2/highgui/highgui.hpp:48,
                 from ./src/coco_demo.c:15:
/usr/local/include/opencv2/core.hpp:49:4: error: #error core.hpp header must be compiled as C++
-----------------------------------------------------------------------------------------------------------------
I not know how to fix it
