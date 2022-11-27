# Lecture_notes_on_LA

## 共編注意事項

1. 如果要顯示證明，請在setting.tex找到以下幾行，並且將pffalse更改為pftrue

~~~latex
\newif\ifpf\pffalse
\newcommand{\pfshow}[1]{\ifpf #1 \else \relax \fi}
~~~

2. 請在每一個定義、定理等等後方標住來源

3. 假如某個定理需要證明，請用附加檔案的方式，並且在input外面包一層/pfshow

