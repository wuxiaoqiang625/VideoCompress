# VideoCompress
Android视频压缩

首先： 视频压缩是硬解的压缩，我最开始接触压缩是FFMpeg压缩，使用的是 https://github.com/chenzhihui28/VideoRecorderAndCompressor ，想尝试的人也可以去看下，但是当我压缩的时候发现，压缩时间很慢，比如压缩1分46秒（253M，ViVO x7 plus）的视频花了2分多钟，具体时间自己可以去测，因为项目需要上传本地视频，本地视频一般很大。。假如是5分钟的视频那么用FFMpeg压缩时间就大于5分钟。。。，而且FFMpeg的命令我真的来不及去玩。。。里面涉及到东西有点多。。

然后： 项目又要很快要把这个压缩功能做完。。。我又没做过这个。。简直是一窍不通。。。 然后实在没法只有github上来找。。。。 之后了解到了硬解，十分感谢这篇文章，大家都可以去看下 https://github.com/Tourenathan-G5organisation/SiliCompressor 这篇文章看了之后，经测试 1分46秒的视频压缩只要1分10几秒左右，如果手机好点，还可以更快。。。。 但是这个文章没有progress，这让我很不方便查看，然后我就去浏览Issuses发现了有个人对这个progress进行了修改 https://github.com/fishwjy/VideoCompressor 我就把两篇文章合在一起使用了。。。。。

最后： 选择本地视频通过 https://github.com/LuckSiege/PictureSelector 来选择的，大家都可以去看下。。。。。

结语： github上的这个Wiki没怎么玩过不知道咋写。。。。。连传图和传gif都不知道咋玩。。。所以效果只有自己去测了， 而且这个项目只是做压缩的一个记录。。。。。如果有其他建议麻烦大家指正。

