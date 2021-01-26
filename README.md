# hardware
基于logisim的8bit cpu，可以播放32*32像素的bad apple
----------------------------------------------------------------------------------------------------------------------------------------
1.compiler目录下是java写的汇编器，可以把指令汇编成二进制，另附source.txt是播放bad apple的源码;
2.instruction format目录下是对指令格式的介绍，以及相应指令应给出的信号(列在了excel表格中);
3.logisim source是logisim平台上的资料，包括电路图都在里面，加载program到inst_sram、data到data_sram可以直接ctrl+k开始运行;
4.video source是bad apple的资源，包括分割好的36*28像素的帧、将32*28像素的帧转换成二进制的python文件...
