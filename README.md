<div align="center">

# $\LaTeX$-in-ICM&MCM：简单全面的美赛LaTeX模板

<!-- 项目徽章 -->
![Version](https://img.shields.io/badge/version-1.2.1-blue.svg)
![License](https://img.shields.io/badge/license-LPPL%201.3c-blue.svg)
![LaTeX](https://img.shields.io/badge/LaTeX-Template-orange.svg)
![MCM/ICM](https://img.shields.io/badge/MCM%2FICM-Optimized-red.svg)
![Downloads](https://img.shields.io/github/downloads/QTH1225/LaTeX-in-ICM-MCM/total.svg?style=flat&color=success&label=Downloads)
![Stars](https://img.shields.io/github/stars/QTH1225/LaTeX-in-ICM-MCM?style=social)
![Last commit](https://img.shields.io/github/last-commit/QTH1225/LaTeX-in-ICM-MCM?color=blue&label=Last%20commit&cacheSeconds=3600)

</div>

一个专为美国大学生数学建模竞赛（MCM/ICM）设计的LaTeX模板库，基于EasyMCM模板进行了深度优化和功能增强，提供完整的论文写作解决方案。本项目在我的[博客](https://qintianhao.com/)同步进行发布。

此外，本项目整理了大量论文写作、绘图以及编程中可能用到的资源，在[其他资源（必看）](#其他资源必看)章节中详细列出。 

<div align="center">

<table> 
   <tr> 
     <td><img alt="模板预览1" src="https://cdn.jsdelivr.net/gh/QTH1225/Blog_Figures/img/20251212111918655.webp"></td> 
     <td><img alt="模板预览2" src="https://cdn.jsdelivr.net/gh/QTH1225/Blog_Figures/img/20251212111918656.webp"></td> 
     <td><img alt="模板预览3" src="https://cdn.jsdelivr.net/gh/QTH1225/Blog_Figures/img/20251212142108823.webp"></td> 
   <tr> 
   <tr> 
     <td><img alt="模板功能1" src="https://cdn.jsdelivr.net/gh/QTH1225/Blog_Figures/img/20251212111635350.png"></td> 
     <td><img alt="模板功能2" src="https://cdn.jsdelivr.net/gh/QTH1225/Blog_Figures/img/20251212111635351.png"></td> 
     <td><img alt="模板功能3" src="https://cdn.jsdelivr.net/gh/QTH1225/Blog_Figures/img/20251212111635352.png"></td> 
   <tr> 
   <tr> 
     <td><img alt="模板功能4" src="https://cdn.jsdelivr.net/gh/QTH1225/Blog_Figures/img/20251212111635353.png"></td> 
     <td><img alt="模板功能5" src="https://cdn.jsdelivr.net/gh/QTH1225/Blog_Figures/img/20251212111635354.png"></td> 
     <td><img alt="模板功能6" src="https://cdn.jsdelivr.net/gh/QTH1225/Blog_Figures/img/20251212111635355.png"></td> 
   <tr> 
 </table>

</div>

> [!CAUTION]
>  在使用本模板前，你至少应该对LaTeX有一定的了解而不是仅仅为了参加美赛而突然放弃Word，你所应该了解的包括但不限于：
>- 基本的LaTeX语法、LaTeX 文档结构与符号
>- 常用的LaTeX宏包（如`amsmath`, `graphicx`, `hyperref`等）
>- 如何编译LaTeX文档（如使用`pdflatex`, `xelatex`, `lualatex`等）
如果你没有LaTeX环境，建议使用**Overleaf**或者**Loongtex**等在线平台进行编译。

另外你需要了解如何处理出现的报错，一般来说可以使用以下几种方法：
- Ask The F~~ucking~~...riendly Web(ATFW，问友好的网络)
- Read The F~~ucking~~...ine Manual(RTFM，读好的的手册)
- Ask The F~~ucking~~...oolish AI(ATFAI，问智能的AI)

## 📁 项目结构

```
LaTeX-in-ICM-MCM/
├── Template/                          # 主模板目录（推荐使用）
│   ├── main.tex                      # 主文档入口
│   ├── part_1_pre.tex                # 问题分析部分（引言、假设、符号说明）
│   ├── part_2_model.tex              # 模型建立部分（模型构建、求解）
│   ├── part_3_conclusion.tex         # 结论部分（结果分析、总结）
│   ├── part_4_Appendix.tex           # 附录部分（代码、数据）
│   ├── new_command.tex               # 自定义命令和宏定义
│   ├── easymcm.sty                   # EasyMCM宏包核心文件
│   ├── img/                          # 图片资源文件夹
│   └── _minted-main/                 # 代码高亮缓存目录
├── Memos/                             # 备忘录和信件模板
│   ├── Letter/                       # 官方信件模板
│   ├── Newsletter_Template/          # 新闻简报模板
│   ├── LaTeX_Publicity_Brochure/     # 宣传手册模板(请使用pdfLaTeX编译)
│   ├── TRMD_Pruefung/                # 测试模板
│   └── XJTLU-Poster-Template-main/   # 海报模板(非A4版面，仅供参考)
├── LICENSE                            # 许可证文件
├── .gitignore                        # Git忽略文件配置
└── README.md                          # 项目说明文档
```

## 📺Bilibili视频教程

<div align="center">
<a href="https://www.bilibili.com/video/BV1eUq6BaExX/?vd_source=c9aec1ceeb3f902c29080b5bd434c5da" target="_blank">
<img src="https://cdn.jsdelivr.net/gh/QTH1225/Blog_Figures/img/20251221093158075.webp" alt="【26开源数模美赛LaTeX模板】视频教程" width="800" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</a>

<br>
<strong>【26开源数模美赛LaTeX模板】免费的专业美赛LaTeX模板+美化的彩页海报+数十个建模资料链接</strong>
<br>
</div>

## ✨ 模板特色功能

### 🎯 美赛专用功能
- **自动控制号设置**：通过`\usepackage[1234567]{easymcm}`自动设置队伍控制号
- **规范摘要格式**：符合MCM/ICM官方要求的Summary格式和排版规范
- **专业字体支持**：提供Times、Palatino等学术论文专用字体选项
- **智能页眉信息**：自动显示队伍编号、页码和章节信息

### 📊 专业排版特性
- **数学公式支持**：完整的AMS-LaTeX数学符号库，支持复杂公式排版
- **高级表格系统**：
  - 三线表格式（toprule/midrule/bottomrule）
  - 跨页长表格（longtable环境）
  - 多行多列表格（multirow/multicolumn）
  - 自适应宽度调整（resizebox和extracolsep）
- **算法排版**：使用`algorithm2e`包支持伪代码排版
- **智能交叉引用**：`hyperref`与`cleveref`联合使用，实现智能引用
- **TikZ绘图支持**：内置TikZ图形库，支持流程图、网络图和统计图表绘制
- **脚注系统**：支持自动编号的脚注功能，可在正文任意位置添加补充说明
- **图文混排功能**：使用`wrapfig`包实现图片与文字的环绕排版
- **引用框样式**：提供专业的引用框样式，用于突出重要内容

### 🎨 代码高亮支持
- **MATLAB代码盒子**：使用`matlab-prettifier`包，支持语法高亮和行号显示
- **Python代码盒子**：与MATLAB统一配色方案，支持语法高亮
- **自动换行功能**：超长代码和注释自动换行，避免溢出问题
- **统一配色方案**：
  - 行号颜色：`darkgray`
  - 关键字颜色：`darkblue`（加粗）
  - 注释颜色：`darkgreen`
  - 字符串颜色：`red!60`（Python特有）

### 📁 模块化设计
- **分章节管理**：将论文分为引言、模型、结论、附录四个独立文件
- **自定义命令**：通过`new_command.tex`集中管理自定义宏命令
- **图片资源管理**：统一的`img/`文件夹管理所有图片资源
- **缓存管理**：自动生成`_minted-main/`目录缓存代码高亮结果

## 🚀 快速开始

### 1. 环境要求
- **LaTeX发行版**：推荐TeX Live 2023+ 或 MiKTeX 22.0+
- **编译引擎**：必须使用XeLaTeX（支持中文和Unicode）
- **额外依赖**：可能需要安装`minted`包（用于代码高亮）

### 2. VSCode配置LaTeX环境（推荐）

#### 2.1 安装LaTeX编译内核
**Windows系统推荐安装TeX Live：**
1. 访问 [TeX Live官网](https://www.tug.org/texlive/) 下载安装包
2. 运行安装程序，选择完整安装（约4GB）
3. 安装完成后，在命令行验证：
   ```bash
   tex --version
   xelatex --version
   ```

**或者安装MiKTeX（体积更小）：**
1. 访问 [MiKTeX官网](https://miktex.org/) 下载安装包
2. 选择基本安装，按需下载宏包
3. 设置自动安装缺失宏包功能

#### 2.2 安装VSCode扩展
在VSCode扩展商店中搜索并安装以下扩展：
- **LaTeX Workshop**：核心LaTeX支持
- **LaTeX Utilities（可选）**：增强功能
- **Code Spell Checker（可选）**：拼写检查
#### 2.3 配置LaTeX编译链
在VSCode中按 `Ctrl+Shift+P`，输入 `Preferences: Open Settings (JSON)`，添加以下配置：

<details>
<summary>点击展开完整VSCode配置（推荐复制使用）</summary>

```json
{
    //---------LaTeX Workshop 配置开始-----------
    // 设置是否自动编译,可选："never", "onSave", "onFileChange"
    "latex-workshop.latex.autoBuild.run": "onSave",
    //文件输出路径，会自动创建temp文件
    //"latex-workshop.latex.outDir": "./temp",
    //右键菜单
    "latex-workshop.showContextMenu": true,
    //从使用的包中自动补全命令和环境
    "latex-workshop.intellisense.package.enabled": true,
    //编译出错时设置是否弹出气泡设置
    "latex-workshop.message.error.show": false,
    "latex-workshop.message.warning.show": false,
    
    // 指定 chktex 的完整路径
    "latex-workshop.chktex.path": "D:/001Softwares/A03Research/texlive/2025/bin/windows/chktex.exe",
    
    // 编译工具和命令
    "latex-workshop.latex.tools": [
        {
            "name": "xelatex",
            "command": "xelatex",
            "args": [
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                "%DOCFILE%"
            ]
        },
        {
            "name": "pdflatex",
            "command": "pdflatex",
            "args": [
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                "%DOCFILE%"
            ]
        },
        {
            "name": "latexmk",
            "command": "latexmk",
            "args": [
                "-synctex=1",
                "-interaction=nonstopmode",
                "-file-line-error",
                "-pdf",
                "-outdir=%OUTDIR%",
                "%DOCFILE%"
            ]
        },
        {
            "name": "bibtex",
            "command": "bibtex",
            "args": [
                "%DOCFILE%"
            ]
        }
    ],
    // 用于配置编译链
    "latex-workshop.latex.recipes": [
        {
            "name": "XeLaTeX",
            "tools": [
                "xelatex"
            ]
        },
        {
            "name": "XeLaTeX*2",
            "tools": [
                "xelatex",
                "xelatex"
            ]
        },
        {
            "name": "PDFLaTeX",
            "tools": [
                "pdflatex"
            ]
        },
        {
            "name": "PDFLaTeX*2",
            "tools": [
                "pdflatex",
                "pdflatex"
            ]
        },
        {
            "name": "BibTeX",
            "tools": [
                "bibtex"
            ]
        },
        {
            "name": "LaTeXmk",
            "tools": [
                "latexmk"
            ]
        },
        {
            "name": "xelatex -> bibtex -> xelatex*2",
            "tools": [
                "xelatex",
                "bibtex",
                "xelatex",
                "xelatex"
            ]
        },
        {
            "name": "pdflatex -> bibtex -> pdflatex*2",
            "tools": [
                "pdflatex",
                "bibtex",
                "pdflatex",
                "pdflatex"
            ]
        }
    ],
    //文件清理。此属性必须是字符串数组
    "latex-workshop.latex.clean.fileTypes": [
        "*.aux",
        "*.bbl",
        "*.blg",
        "*.idx",
        "*.ind",
        "*.lof",
        "*.lot",
        "*.out",
        "*.toc",
        "*.acn",
        "*.acr",
        "*.alg",
        "*.glg",
        "*.glo",
        "*.gls",
        "*.ist",
        "*.fls",
        "*.log",
        "*.fdb_latexmk"
    ],
    //设置为onFaild 在构建失败后清除辅助文件
    "latex-workshop.latex.autoClean.run": "onFailed",
    // 使用上次的recipe编译组合
    "latex-workshop.latex.recipe.default": "lastUsed",
    // 用于反向同步的内部查看器的键绑定。ctrl/cmd +点击(默认)或双击
    "latex-workshop.view.pdf.internal.synctex.keybinding": "double-click",
    //设置查看PDF的工具，可选"browser","tab","external"
    "latex-workshop.view.pdf.viewer": "tab",
    "workbench.editor.empty.hint": "hidden",
    "editor.fontSize": 16,
    "github.copilot.nextEditSuggestions.enabled": true,
    "git.enableSmartCommit": true,
    "git.autofetch": true,
    "git.confirmSync": false,
    "debug.allowBreakpointsEverywhere": true,
    "terminal.integrated.defaultProfile.windows": "Command Prompt",
    "editor.fontFamily": "FiraCode Nerd Font,Consolas, 'Courier New', monospace",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.editorAssociations": {
        "*.copilotmd": "vscode.markdown.preview.editor",
        "*.pdf": "default"
    },
    "workbench.settings.applyToAllProfiles": [

    ],
    
    //---------LaTeX Workshop 配置结束-----------
}
```

</details>

#### 2.4 配置代码片段（可选，自行配置）
创建LaTeX代码片段，按 `Ctrl+Shift+P`，输入 `Preferences: Configure User Snippets`，选择 `latex.json`，此处为一个示例。

```json
{
    "Table Environment": {
        "prefix": "tableInsert",
        "body": [
            "\\begin{table}[htbp]",
            "\\centering",
            "\\caption{${1:Table Caption}}",
            "\\label{tab:${2:label}}",
            "\\begin{tabular}{${3:ccc}}",
            "\\toprule",
            "${4:Header 1} & ${5:Header 2} & ${6:Header 3} \\\\\\",
            "\\midrule",
            "${7:Data 1} & ${8:Data 2} & ${9:Data 3} \\\\\\",
            "\\bottomrule",
            "\\end{tabular}",
            "\\end{table}"
        ],
        "description": "Insert a table environment"
    }
}
```

### 3. 使用步骤
1. **获取模板**：克隆或下载本仓库到本地
2. **打开项目**：在VSCode中打开 `Template` 文件夹
3. **配置基本信息**：编辑`main.tex`文件：
   ```latex
   \usepackage[1234567]{easymcm}  % 将1234567替换为你的队伍控制号
   \problem{A}                   % 将A替换为你的题号（A/B/C/D/E/F）
   ```
4. **编写内容**：分别在四个章节文件中编写内容：
   - `part_1_pre.tex`：问题分析、假设、符号说明
   - `part_2_model.tex`：模型建立、求解过程
   - `part_3_conclusion.tex`：结果分析、结论总结
   - `part_4_Appendix.tex`：代码、数据等附录内容
5. **编译文档**：
   - **VSCode方式**：按 `Ctrl+Alt+B` 自动编译，选择"xelatex -> bibtex -> xelatex*2"编译链
   - **命令行方式**（支持参考文献）：
   ```bash
   xelatex main.tex
   bibtex main.aux
   xelatex main.tex
   xelatex main.tex  # 编译四次确保参考文献和交叉引用正确
   ```

### 3. 常用功能示例

**插入表格**（支持跨页长表格）：
```latex
\begin{longtable}{@{\extracolsep{\fill}}ccccc@{}}
\caption{参数分析表}\\ \toprule[2pt]
\multicolumn{1}{m{2.5cm}}{\centering \textbf{参数}} & \multicolumn{1}{m{2cm}}{\centering \textbf{类型}} & \multicolumn{1}{m{3cm}}{\centering \textbf{范围}} & \multicolumn{1}{m{2.5cm}}{\centering \textbf{默认值}} & \multicolumn{1}{m{2cm}}{\centering \textbf{敏感度}} \\
\midrule
$\\alpha$ & Continuous & [0, 1] & 0.5 & High \\
\end{longtable}
```

**插入代码**（支持MATLAB和Python）：
```latex
% MATLAB代码
\begin{matlab}{MATLAB代码标题}{matlab:label}
% 你的MATLAB代码
A = [1, 2, 3; 4, 5, 6; 7, 8, 9];
result = sum(A, 2);
\end{matlab}

% Python代码
\begin{python}{Python代码标题}{python:label}
# 你的Python代码
def calculate_sum(matrix):
    return [sum(row) for row in matrix]
\end{python}
```

## ⚙️ 配置选项

### 字体选择
模板支持多种专业字体，在`main.tex`中取消注释相应行：
- `\usepackage{mathptmx}` - Times字体（中规中矩）
- `\usepackage{palatino}` - Palatino字体（官方推荐）

### 代码样式定制
在`main.tex`中修改代码盒子定义来自定义：
- 行号样式：`numberstyle`
- 关键字样式：`keywordstyle`
- 注释样式：`commentstyle`
- 字符串样式：`stringstyle`

## ⚠️ 注意事项

### 编译要求
1. **必须使用XeLaTeX**：不支持pdfLaTeX或LuaLaTeX
2. **编译两次**：确保交叉引用和目录正确生成

### 文件管理
1. **图片路径**：所有图片应放在`img/`文件夹中
2. **章节分离**：各章节内容在对应的`.tex`文件中编写
3. **自定义命令**：新增命令应在`new_command.tex`中定义

### 排版规范
1. **表格宽度**：使用`resizebox`或`extracolsep`控制表格宽度
2. **代码长度**：长代码建议放在附录部分
3. **参考文献**：使用BibTeX管理，格式应符合美赛要求

## 🔧 问题解决

### 常见问题
1. **编译错误**：检查是否使用XeLaTeX，是否编译两次
2. **代码显示异常**：检查代码中是否有特殊字符需要转义
3. **表格排版问题**：合理设置列宽，避免使用过大的`resizebox`

## 其他资源（必看）

### 🎨 绘图与可视化工具
#### 图表制作工具
- [Draw.io](https://www.drawio.com/) - 免费在线图表工具，支持流程图、UML图等
- [迅捷画图](https://huatu.bangongtuku.com/) - 在线流程图和思维导图工具，支持团队协作
- [书图网](https://shutu.cn/center/newfile) - 在线图表制作平台，支持多种图表类型
- [ECharts](https://echarts.apache.org/zh/index.html) - 百度开源的可视化库，功能强大的图表组件
- [RawGraphs](https://www.rawgraphs.io/) -开源数据可视化工具，支持多种图表类型
- [Inkscape](https://inkscape.org/) - 免费开源的矢量图形编辑器，支持创建和编辑矢量图形
- [ImageGP](https://www.bic.ac.cn/ImageGP/) - 生物信息学图像处理平台，提供专业绘图工具
- [Color Hex](https://www.color-hex.com/) - 颜色代码查询工具，提供丰富的配色方案
#### 地图与数据可视化
- [阿里云DataV](https://datav.aliyun.com/portal/school/atlas/area_selector) - 阿里云数据可视化平台，提供丰富的地图组件
- [NBCharts地图工具](https://www.nbcharts.com/map/map.php) - 在线地图制作工具，支持多种地图类型
- [CS Academy Graph Editor](https://csacademy.com/app/graph_editor/) - 网络图绘图网址，比较简单

#### 图标与图片资源
- [Iconfont](https://www.iconfont.cn/) - 阿里巴巴矢量图标库，中文图标资源丰富
- [The Noun Project](https://thenounproject.com/) - 海量图标资源库，提供高质量的矢量图标
- [Freepik](https://www.freepik.com/search?format=search&query=tree) - 免费矢量图库，提供高质量的插画和图片资源


### 📝 LaTeX与学术写作工具
#### 排版工具
- [Overleaf](https://www.overleaf.com/) - 在线LaTeX编辑器，支持实时协作和版本控制
- [Typst](https://typst.app/) - 现代排版系统，提供简洁的文档编写体验
- [LoongTeX](https://www.loongtex.com/) - 中文LaTeX编译网站，提供模板和教程
  
#### 公式与符号工具
- [LaTeX Live Editor](https://www.latexlive.com/) - 在线LaTeX公式编辑器，实时预览数学公式
- [Detexify](https://detexify.kirelabs.org/classify.html) - LaTeX符号识别工具，手绘识别数学符号
- [Tables Generator](https://www.tablesgenerator.com/) - 在线表格生成器，支持LaTeX表格代码生成
- [Google Fonts](https://fonts.google.com/) - 免费字体库，提供多种专业字体

#### 写作辅助工具
- [写作猫](https://xiezuocat.com/) - AI写作助手，支持文档润色和语法检查
- [Ludwig](https://app.ludwig.guru/) - 英文写作助手，提供句子结构和词汇建议
- [曼彻斯特学术短语库](https://www.phrasebank.manchester.ac.uk/) - 学术写作短语库，提供专业表达方式
- [Panda985](https://panda985.com/) - 学术写作工具，提供论文模板和写作指导
- [Deepl](https://www.deepl.com/zh/translator) - 中文翻译工具，支持多语言翻译 
- [百度翻译API](https://fanyi-api.baidu.com/) - 百度翻译开放接口，支持多语言翻译
- [Rewordify](https://rewordify.com/index.php) - 文本简化工具，帮助理解复杂英文文本

#### 代码处理
- [Ubuntu Paste](https://paste.ubuntu.com/p/7dwyVCCKw9/) - 代码片段高亮平台
- [Code in Word](https://codeinword.com/) - 代码片段高亮平台
- [Snippet Generator](https://snippet-generator.app/) - 代码片段生成器，支持多种编辑器格式

#### LaTeX学习资源
- [华东师范大学LaTeX资源](https://math.ecnu.edu.cn/~jypan/Latex/index.html) - LaTeX学习资源集合，包含教程和模板
- [LaTeX2e教程](https://www.latex-project.org/news/latex2e-news/) - LaTeX2e官方教程，详细介绍LaTeX的相关使用方法
- [Overleaf 30分钟LaTeX教程](https://cn.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes) - 快速入门LaTeX的官方教程，适合初学者
- [正确写作美国大学生数学建模竞赛论文](https://zh.z-library.sk/book/117304968/32dc10/%E6%AD%A3%E7%A1%AE%E5%86%99%E4%BD%9C%E7%BE%8E%E5%9B%BD%E5%A4%A7%E5%AD%A6%E7%94%9F%E6%95%B0%E5%AD%A6%E5%BB%BA%E6%A8%A1%E7%AB%9E%E8%B5%9B%E8%AE%BA%E6%96%87.html) - 美赛论文写作指南，包含格式规范和注意事项
- [LaTeX数学符号速查表](https://www.cmor-faculty.rice.edu/~heinken/latex/symbols.pdf) - 完整的LaTeX数学符号参考手册，方便查找特殊符号
- [LaTeX笔记教程](https://github.com/BenjaminGor/Latex_Notes_Tutorial) - 包含LaTeX基础、常用宏包、表格、图表、数学公式等的详细笔记教程，适合初学者和进阶用户
### 📊 数据处理与分析工具
#### 统计分析工具
- [SPSSPRO](https://www.spsspro.com/) - 在线统计分析平台，提供专业的统计分析功能
- [BioLadder](https://www.bioladder.cn/web/#/toolSet) - 生物信息学工具集，提供多种数据分析工具
- [Tableau](https://www.tableau.com/) - 数据可视化工具，提供强大的数据分析和可视化功能
#### 数据资源与知识库
- [Our World in Data](https://ourworldindata.org/) - 全球数据可视化平台，涵盖多领域统计数据
- [Towards Data Science](https://towardsdatascience.com/) - 数据科学社区，分享数据分析和机器学习知识
- [Wolfram MathWorld](https://mathworld.wolfram.com/) - 数学百科全书，提供详细的数学概念解释
- [Connected Papers](https://www.connectedpapers.com/) - 论文关联分析工具，可视化文献关系网络

### 🤖 AI与智能工具
#### AI编程助手
- [Trae AI](https://www.trae.cn/) - 智能代码助手，提供AI编程支持
- [Cursor编辑器](https://cursor.com/cn) - AI驱动的代码编辑器，智能代码补全
- [GPTGod在线](https://gptgod.online/) - AI对话平台，支持多种AI模型
- [Grok AI](https://grok.com/) - xAI开发的AI助手，提供实时信息查询
- [Gemini AI](https://gemini.google.com/app) - Google开发的AI助手应用，支持多模态交互和智能对话

#### AI工具配置
- [ZCF项目](https://github.com/UfoMiao/zcf) - 一键式配置Claude Code，无需复杂设置
- [Claudia AI助手](https://getclaudia.org/) - 有力的Claude Code GUI界面
- [Claude Code切换工具](https://github.com/farion1231/cc-switch) - 用于切换Claude Code模型的GitHub项目，方便管理不同版本
- [Metaso](https://metaso.cn/) - AI搜索工具，智能信息检索和整理
- [Labnana](https://labnana.com/zh) - 扩展图或者文生图的模型，需要签到赚取积分
- [Banana Prompt Quicker](https://glidea.github.io/banana-prompt-quicker/) - 提示词优化工具，提升AI对话效果

#### 学习资源
- [Deep Learning项目](https://github.com/Mikoto10032/DeepLearning) - 深度学习学习资源，包含教程和代码示例
- [Vibe Coding](https://github.com/tukuaiai/vibe-coding-cn) - Vibe Coding指南，提供一些AI编程的使用方法和技巧

### 📄 Word与办公工具
- [Zotero中文社区](https://zotero-chinese.com/) - 文献管理工具Zotero的中文支持社区，提供使用教程和插件
- [Amyxun](https://www.amyxun.com/) - Axmath与AxGlyph介绍网址
- [WordTeX](https://tomwildenhain.com/wordtex/) - 如何在Word上以假乱真的模仿LaTeX文档

## 往年美赛资源
- [2025E题F奖](https://github.com/LUKEQ420/MCM-ICM-2025-E-Nitrogen-Cycling-Model) - 来自[@LUKEQ420](https://github.com/LUKEQ420)的2025年E题F奖解题模型
- [2023年B题F奖](https://github.com/GuangLun2000/COMAP-MCM-2026) - 来自[@GuangLun2000](https://github.com/GuangLun2000)的2023年B题F奖解题模型

## 特别感谢
- **[EasyMCM项目](https://github.com/xjtu-blacksmith/easymcm)** - 提供了基础模板，为本项目奠定了基础
- **[LaTeX工作室](https://www.latexstudio.net/)** - 持续提供的支持和资源，帮助解决了许多问题
- **[Maki's Lab](https://www.maki-math.com/)** - 分享了丰富的LaTeX使用经验和技巧
- **[Cai Hanlin(Lance)](https://caihanlin.com/)** - 分享了美赛的一些经验与建议
- **[Gilles Castel](https://castel.dev/)** - LaTeX+Vim的1700页笔记工作流给我LaTeX使用的很多启发
- **[Levitate Qian](https://levitate-qian.github.io/)** - 个人技术博客作者，分享了丰富的LaTeX使用经验和技巧
- **[B站-清风数学建模](https://space.bilibili.com/52614961?spm_id_from=333.337.0.0)** - 提供了数学算法、排版等新手教程，十分友好
- **[B站-跟着浩然玩转高考物理](https://space.bilibili.com/384497590?spm_id_from=333.337.0.0)** - 分享了美赛的一些经验与得奖技巧
- **[米醋电子工作室](https://www.micu.wiki/)** - 提供了一些AI编程的使用方法和技巧
- **Overleaf模板资源** - 提供了多个实用的LaTeX模板，可以作为彩页或者海报使用
  - **[LaTeX publicity brochure template](https://cn.overleaf.com/latex/templates/latex-publicity-brochure/dbqxssdqyjtv)** - 宣传手册模板，现代风格
  - **[Newsletter template](https://cn.overleaf.com/latex/templates/newsletter-template/nzvznvdbdqpl)** - 新闻简报模板，内容分区
  - **[TRMD Pruefung template](https://cn.overleaf.com/latex/templates/trmd-pruefung/jyshhkzszhsb)** - 报纸模板，简洁双栏展示
  - **[XJTLU Poster Template](https://github.com/yaoshanliang/XJTLU-Poster-Template)** - 学术海报模板，会议格式

❗特别说明：本项目实际参考了互联网上很多优秀作者的资源（包括帖子、随笔、问答等），但是因为我的时间和精力有限，所以不能一一列出所有的参考资源，在此深感抱歉。如果您认为本项目参考了您的资源，欢迎联系我，我会在项目中添加您的资源链接。
## 🤝 贡献指南

欢迎提交Issue和Pull Request来改进模板，或者添加你的美赛资源，但是我可能更新速度比较慢。
1. **Bug报告**：详细描述问题现象和复现步骤
2. **功能建议**：说明需求背景和预期效果
3. **代码贡献**：遵循现有代码风格和文档规范
4. **添加美赛资源**：如果有相关的美赛资源（如模板、代码示例等），欢迎添加

## 📄 许可证

本项目采用 [LaTeX Project Public License 1.3c](https://www.latex-project.org/lppl/) (LPPL 1.3c)。

**LPPL许可证的主要特点：**
- **修改自由** — 允许用户修改和分发修改后的版本
- **维护状态** — 要求修改后的作品必须明确标识其与原始作品的关系
- **文件完整性** — 确保LaTeX文件的完整性，避免不兼容的修改
- **版本控制** — 支持版本管理，便于维护和更新

**主要条款：**
- 您可以自由使用、修改和分发本模板
- 修改后的版本必须使用不同的文件名或版本号
- 必须保留原始许可证声明和版权信息
- 修改后的版本不能声称是原始作品的官方版本

基于EasyMCM v5.1模板开发，遵循相应开源协议。Memo目录下的文件均遵循作者的原开源协议。

## 作者寄语
作者从大一开始作为论文手参与数模竞赛，在四年时间中论文类比赛参加了十几场，累计写过的字数约有15w左右。在2022、2023年参加了3次美赛全是S奖，但是我也一直没有放弃学习，所以美赛的经验也为我后来其他竞赛提供了不少帮助。

我想说的是，一直致力于打数模竞赛很好，打一两次觉得不适合自己放弃了也没事。最重要的是不能因为打数模竞赛的结果而放弃学习，放弃接受新知识。

<div align="center">
<img src="https://cdn.jsdelivr.net/gh/QTH1225/Blog_Figures/img/20251212150213361.webp" alt="凌晨在学院楼写完论文所拍摄" style="max-width: 80%; height: auto;">

*凌晨在学院楼写完论文所拍摄*
</div>

## Star History
如果您觉得本项目对您有帮助，欢迎给我一个star⭐，谢谢！
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=QTH1225/LaTeX-in-ICM-MCM&type=Date&theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=QTH1225/LaTeX-in-ICM-MCM&type=Date" />
  <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=QTH1225/LaTeX-in-ICM-MCM&type=Date" />
</picture>


