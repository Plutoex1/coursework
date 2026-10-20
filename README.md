# Курсовая работа

Автор: Рязанов Григорий Алексеевич, группа P3311.

## Содержимое
- `report/main.tex` — главный файл LaTeX, `report/sections/` — главы, `report/images/` — рисунки
- `report/report.pdf` — собранный отчёт

## Как собрать PDF
    cd report
    pdflatex main.tex

Если в отчёте используется библиография BibTeX: `bibtex main`, затем ещё два раза `pdflatex main.tex`.
