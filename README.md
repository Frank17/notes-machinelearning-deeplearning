# notes-machinelearning-deeplearning
统计机器学习-深度学习-神经网络等的学习笔记

如果有需要自行编译`tex`文件，推荐使用texlive，并使用xelatex。作者使用VSCode + Latex Workshop + TexLive 2018编译，编译工具配置如下：
```json
"latex-workshop.latex.recipes": [
    {
      "name": "xelatex",
      "tools": [
        "xelatex"
      ]
    },
    {
      "name": "xelatex ➞ bibtex ➞ xelatex × 2",
      "tools": [
        "xelatex",
        "bibtex",
        "xelatex",
        "xelatex"
      ]
    }
  ]
```