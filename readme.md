# VINS-MONO-for-Opencv4
原版的 VINS-MONO 有许多 CV_XXX ，但是这种已经不适应于 opencv4 。本项目对所有 CV_XXX 进行了修改，改为对应新版的 cv::XXX 。实测 catkin_make 不报错。