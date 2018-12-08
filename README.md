## 如何使用

### 编辑以下文件

- main.cfg: 包含了论文中需要填写的项目，比如论文名称等。论文的致谢部分也放在了这里

- abstract.cfg: 包含了论文的中英文摘要

- main.tex: 论文的主体、附录、外文译文，目前填充的是示例，对照生成的PDF熟悉代码

- bib.ref: 论文的参考文献库

- BUPTthesisbachelor.sty: 论文的格式，包含页眉页脚等

### 用素材填充以下文件夹

- pictures:将图片放入该文件夹

- docs：将封面（cover）、诚信声明（statement）、外文文献原文（translation）、任务书（task）、成绩评定表（scoreTable）、开题报告（openingReport）和中期检查表（interimReport）的PDF放入该文件夹。为了保持清晰度，请在从Word输出PDF时尽可能选择**高质量**的设置（修正官方缺陷的封面及其他材料的word版已放入该文件夹，编辑并保存为PDF即可）

教务处官方相关模板请访问https://jwc.bupt.edu.cn/list/list.php?p=9_38_1

在TeXworks中编译main.tex即可，main.pdf即最终输出。

**注意：如果你在使用中遇到问题，请查看下方FAQ或到Issue板块寻找是否有其它使用者给出的解决方案。**


## 编译

在TeX Live环境下

先用XeLaTeX编译一遍；

再用BibTeX编译一遍；

再用XeLaTeX编译一遍。

（如果里面引用号码没有显示，就再XeLaTeX编译一遍。）