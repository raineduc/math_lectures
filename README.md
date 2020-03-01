# math_lectures
Конспекты лекций по математике

## Инструкция по сборке pdf
1. Необходимы MikTex, pandoc
2. Используем команду для сборки

        pandoc Lecture1.md --pdf-engine=xelatex --variable mainfont="..." --variable mathfont="..." -o Lecture1.pdf
    
Вместо многоточия `...` пишем шрифты, они должны быть установлены на компьютере. Я использовал `mainfont="Times New Roman` и `mathfont="Latin Modern Math`
