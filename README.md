# 陽明交通大學碩博士論文 XeLaTeX 模板

[nycu-thesis]((https://github.com/indigo40123/NYCU-Thesis-Template)
Template are developed based on XeLaTeX + xeCJK.

## 下載
  你可以 clone 這個 repos, 或是到[這裡](https://github.com/indigo40123/NYCU-Thesis-Template)下載最新版本

## 快速上手
* Use command line

  ```
  $ make
  ```

* Change the xelatex option in IDE, then build main.tex

  ```
  xelatex -synctex=1 -shell-escape -interaction=nonstopmode %.tex
  ```
  * thesis.cls 會根據你目前使用的作業系統選擇要使用的中文字型, 請設定 -shell-escape 開啟這個功能.

    (這樣你和你的指導教授用不同作業系統寫論文時, 就不用每次重新設定中文字型啦)

## 說明
   進階的使用教學請參考 [README.pdf](https://github.com/indigo40123/NYCU-Thesis-Template/README.pdf)


## Acknowledgement
   此模板的前身是交大 borting chen同學的 [nctu-thesis](https://github.com/borting/nctu-thesis) 
   此模板的貢獻為更新陽交大的封面頁,Latex設定及格式還參考了Chun Sing Leung學長以及以下幾位的模板. Thank you.
   
* 台科大 hdj 與 saiba 兩位學長的 [ntust-thesis template](https://code.google.com/archive/p/ntust-thesis/downloads)
* 交大 Po-hao Huang 同學的 [nctu-thesis template](https://github.com/Po-haoHuang/nctu-thesis)
* 交大 Chiehmin (FatMinMin) 同學的 [nctu-thesis](https://github.com/chiehmin/nctu-thesis)
* 台大 [qcl](https://github.com/qcl/qcl-master-thesis) 與 [tzhuan](https://github.com/tzhuan/ntu-thesis) 兩位同學的 ntu-thesis template

## License
   此模板係採用[創用 CC 姓名標示-非商業性-相同方式分享 3.0 台灣 授權條款](https://creativecommons.org/licenses/by-nc-sa/3.0/tw/legalcode)授權.
