# eyeSee
## 基于openCV实现运动眼球瞳孔的动态识别

.附上粗制滥造的rar（rar解压到D盘根目录可以解决下面路径问题）

.idea 启动配置：-Djava.library.path=D:/opencv/build/java/x64;D:/opencv/build/x64/vc14/bin（加上对应openCV的路径）

.代码中  static{ System.load("D:\\opencv\\build\\java\\x64\\opencv_java341.dll"); } 也需要进行对应修改

.项目内需要加入jar包，路径：D:\opencv\build\java\opencv-341.jar

**本项目只针对项目内视频制作瞳孔捕捉方案，要编写出自适应的瞳孔捕捉需要更多及更深入的了解。**
