# UCAS_Thesis
The newest template of thesis for UCAS.

鉴于国科大提供的最新模板有bug，根据国科大最新版的毕业论文写作要求(2023年开始使用)修改[原先国科大模板](https://github.com/mohuangrui/ucasthesis)得到最新的模板，最后得到该模板。

修订了以下问题或有以下更新：
- 英文参考文献省略多个作者应用 et al 而不是“等”；
- 图目录和表目录标题更改并合并在一起，并将页眉改为“图表目录”，我直接将\leftmark = 图表目录 比重定义fancy页面要简单，不易出错；
- 附录的章用中文汉字数字编号，不再使用字母编号，几章几节则使用“附1.1”等，公式编号也采用(附1-3)之类的；
- 附录中的图表名称全改为“附图”和“附表”，为了使得“附图”和“附表”能显示在图表目录里，只能将“附图1-1”一起定义为该图的标签，引用时直接“见\ref{fig:label}”即可，无需再写“见图~\ref{fig:label}”；表类似。因此本模板不支持双语的caption；
- 公式编号不会在比chapter低的章节(如section)内刷新。

如果遇到生僻字无法显示的问题见[链接](https://github.com/mohuangrui/ucasthesis/wiki/%E5%AD%97%E4%BD%93%E9%85%8D%E7%BD%AE)

如有新的bug或者还有哪里不符合国科大最新版毕业论文要求的地方，欢迎向我报错，请联系guoxiao@nao.cas.cn或guoxiao17@mails.ucas.ac.cn也欢迎大家修正或维护我更新的模板。
