# NJU-Thesis

　　本项目提供了一个用于排版南京大学学位论文的LaTeX模板。该模板基于校友[Haixing-Hu的模板](https://github.com/Haixing-Hu/nju-thesis)，修复了若干Bug，增加和优化了一些功能细节。可根据文档注释说明，将本模板修改为本科/硕士/博士学位论文模板。  
  
## 使用说明:
* 默认Windows系统下，**安装[ctex](http://www.ctex.org/CTeXDownload/)完整版**。Mac,Linux操作系统需按照sample.tex中的注释说明，修改字体等参数。已给出样例sample.tex，编辑修改该文件即可。
* **必须使用XeLaTeX**。建议使用TeXworks编辑，选择**XeLaTeX+MakeIndex+BibTex**编译运行。WinEdt需要使用**UTF-8**编码打开.tex文件，并且使用XeLaTeX编译。
* 切换本科生、研究生、博士生论文模版，需修改.tex文件中\documentclass[参数]
* 参数twoside/oneside指定排版的文档为双面/单面格式，如果论文双面打印，则建议用twoside（twoside会使得chapter章节从奇数页开始，即纸张的正面开始，因此会出现一些空白的页面）。
* 使用bibtex文献管理，用编辑器编辑sample.bib文件即可。或使用[JabRef](http://www.jabref.org/)打开

## 文件说明:
|文件(夹)|说明|
|-|-|
|sample.tex | 示例文档，可作为学位论文的基本模板|
|sample.bib | 示例文档的参考文献数据库|
|njuthesis.cls | 模板类文件|
|njuthesis.cfg | 模板配置文件|
|njulogo.eps | 南京大学校徽图片|
|njuname.eps | 南京大学校名图片|
|gbt7714-2005.bst | 符合国标GB/T 7714-2005 的参考文献样式文件|
|figures/ | 示例文档图片目录|

## 参考文献格式说明
严格遵循中国国家标准[《GB/T 7714-2005: 文后参考文献著录规则》][gbt7714-2005]   
详细信息见该项目：[GBT7714-2005-BibTeX-Style](https://github.com/Haixing-Hu/GBT7714-2005-BibTeX-Style)

[gbt7714-2005]: https://github.com/njuHan/njuthesis-nju-thesis-template/blob/master/%E3%80%90GB_T%207714-2005%E3%80%91%E6%96%87%E5%90%8E%E5%8F%82%E8%80%83%E6%96%87%E7%8C%AE%E8%91%97%E5%BD%95%E8%A7%84%E5%88%99.pdf
