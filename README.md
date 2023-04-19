# UCAS_Thesis
The newest template of thesis for UCAS.

中国科学院大学毕业论文模板（2023年起）

鉴于国科大提供的最新模板有bug，根据国科大最新版的毕业论文写作要求(2023年开始使用)修改[原先国科大模板](https://github.com/mohuangrui/ucasthesis)得到最新的模板，最后得到该模板。

修订了以下问题或有以下更新：
- 设置了1.25倍行距；
- 英文参考文献省略多个作者应用 et al 而不是“等”, 只有两位作者的话显示为 Guo & Lu (2020)；
- 取消了参考文献里的作者自动大写；
- 参考文献提供DOI后自动生成相应的文章链接；
- 图目录和表目录标题更改并合并在一起，并将页眉改为“图表目录”，我直接将\leftmark = 图表目录 比重定义fancy页面要简单，不易出错；
- 附录的章用中文汉字数字编号，不再使用字母编号，几章几节则使用“附1.1”等，公式编号也采用(附1-3)之类的；
- 附录中的图表名称全改为“附图”和“附表”，为了使得“附图”和“附表”能显示在图表目录里，只能将“附图1-1”一起定义为该图的标签(\thefigure)，并定义图的前缀\figurename为空，引用时直接“见\ref{fig:label}”即可，无需再写“见图~\ref{fig:label}”；表类似。因此本模板不支持双语的caption；
- 参考文献放在附录的前面；
- 公式编号不会在比chapter低的章节(如section)内刷新。
- 附录的奇数页页眉改为“附\quad录”, 在附录前加上\renewcommand{\leftmark}{附\quad录}。
- 图表的编号与caption内容之间间隔一个汉字的大小，在文档开始加上\usepackage{caption} \captionsetup{labelsep=quad}.

## 其他常见问题
- 如果遇到生僻字无法显示的问题见[链接](https://github.com/mohuangrui/ucasthesis/wiki/%E5%AD%97%E4%BD%93%E9%85%8D%E7%BD%AE)。
- 如果图表的caption太长，不想在目录中显示，可以把caption改为\caption\[ 目录中显示的标题\]{文中显示的很长的描述}

其他问题还可以参见[https://github.com/mohuangrui/ucasthesis/wiki/](https://github.com/mohuangrui/ucasthesis/wiki/)

如有新的bug或者还有哪里不符合国科大最新版毕业论文要求的地方，欢迎向我报错，请联系guoxiao@nao.cas.cn或guoxiao17@mails.ucas.ac.cn也欢迎大家修正或维护我更新的模板。


https://github.com/guoxiaowhu/UCAS_Thesis

郭潇
