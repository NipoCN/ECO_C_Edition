# ECO_C_Edition

一、目标
冯如杯目标跟踪，将ECO算法转换为C语言版本

二、Guideline
1，完整读一遍代码，勾勒出算法框架
2，分工：feature extraction部分和implemention部分。后面implemention部分比较复杂，可以多找两个人来读和写。
3，找出所有的依赖于第三方的库和代码，比如各种滤波用到的fft什么的之类的，找到用c的话用哪些库来代替（比如c下面有很高效的fftw算法库可以用）
4，按照分工，从上至下一个模块一个模块用c来重新，并进行模块测试，结果跟matlab来对比，确保模块功能正确
5，把各个模块进行集成。

三、测试
使用MATLAB的unit test功能

四、Github操作
使用Github Desktop，修改后提交使用PUSH，获得更新使用PULL

五、运行
1.Download matconvnet ZIP file from https://github.com/vlfeat/matconvnet and unpack it in the external_libs/matconvnet/ folder of the repository.

2.Download PDollar Toolbox ZIP file from https://github.com/pdollar/toolbox and unpack it in the external_libs/pdollar_toolbox/ folder of the repository.

3.Start Matlab and navigate to the repository.

Run the install script:

|>> install

Run the demo script to test the tracker:

|>> demo_ECO
