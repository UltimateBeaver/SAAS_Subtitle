EAAS_Subtitle
=============

文件目录
-------------

根目录下包含两个文件夹: ```\srt_en``` 和 ```\srt_sc```
* ```\srt_en```中包含所有课程英文字幕文件, 已全部上传, 共114个
* ```\srt_sc```中包含有道翻译已经返回的中文字幕文件, 截止2014.4.6共12个

工作机制
-------------

翻译校对以周为单位，每周五
* 有道: 给我们当周新翻译好的字幕和对上周校对内容的修改
* 我们: 返回当周的校对成果(校对内容是有道上一周翻译的字幕)

校对机制
-------------

翻译校对的工作从下周开始，每一个字幕文件由两个人负责，一人审一遍。校对方法如下：

* 用词不当等小错直接在中文字幕文件中原地更改
* 句意错误或几句话不通顺等大错请用{ }将出错的部分括起来，留给有道重新翻译

在校对的过程中，有以下几点需要注意：

* 校对完成后，请按以下格式commit后再push
```
git commit -am “xxxx x” \\其中xxxx为校对者姓名拼音, x为一整数, 取0表示第一次校对，取1表示确认有道重翻的结果
git commit -am “yinhezheng 0” \\表示校对者为yinhezheng, 是第一次校对
```
* 所有任务(对新内容的校对和对有道重翻内容的确认)请在**每周四晚12:00之前**完成
* 任务完成时间以最后一次commit为准

> 经过我们校对的内容将直接放到网上作为课程的字幕文件，所以请大家务必认真对待，谢谢！

任务分配
--------------


