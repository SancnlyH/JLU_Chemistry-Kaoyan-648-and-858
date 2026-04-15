# JLU_Chemistry-Kaoyan-648-and-858
# 历年真题试卷重制计划

提供吉林大学化学专业的考研真题与答案解析，以及一些可能用得上的自编资料。

[![LaTeX](https://img.shields.io/badge/LaTeX-2e-008080.svg)](https://www.latex-project.org/)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)



项目主要由@Miyanaga_Saki完成(或Saki)，github项目owner并非主要参与者，甚至并非JLU学生，但是也会进行维护。

试卷识别采用OCR+GraphRAG实现，最终生成的.tex文件仅经过了很粗略的审校。如果您发现成品出现排版或识别错误，欢迎提出。

## 目录结构

(设想的)架构：
```text
Inorganic_Exams/          # 也可能是别的
├── main.tex              # main文件
├── 2002exam.tex          # 2002年试卷纯文本内容
├── 2003exam.tex          # 2003年试卷纯文本内容
├── ...
├── figures/              # 图片存放处
├── build/                # 编译生成的PDF文件存放处
└── xxx.pdf               # 应需求，现在在外面会放一份改好名字的编译好的pdf文件

```

## TODO
- 分析化学
- 有机化学              <span style="color: gray; font-size: 0.9em;">- 结构式识别尚有难题，等待并心怀希望吧……</span>
- 无机化学答案和解析
- 有机化学答案和解析
- 物理化学答案和解析
- 分析化学答案和解析
- JLU期末考试试题

## 许可证

本项目采用 CC BY-NC-SA 4.0 协议开源。
你可以自由地分享和修改本项目的代码用于学习和交流，但请务必保留原作者署名，且不得用于任何商业盈利行为。

This project is licensed under the CC BY-NC-SA 4.0 License.

You are free to use, share, and adapt the material for non-commercial purposes,
as long as proper attribution is given and derivative works are shared alike.

## 致谢

感谢JLU编写真题的教师。这些真题都是大学教师的劳动成果，著作权属于大学和大学教师们。但是由于中国教育的特殊性和中国法律的相关条款，考试题目一般是可以免费分享的。因此，我们在这里把真题免费分享给大家。  

感谢@SancnlyH @Natsum1 对于手写试卷识别的贡献，但相关项目不便开源，敬请谅解
