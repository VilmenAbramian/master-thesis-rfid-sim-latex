
# Master Thesis — RFID Simulation (LaTeX)

Текст магистерской диссертации на русском языке в формате LaTeX.

## Структура проекта

Документ разбит на части (по главам), которые хранятся в отдельных файлах. Настройки стилей и пакетов, а также управляющие переменные тоже вынесены в отдельные файлы.

```
observe.tex         # основной файл запуска
observe.bib         # библиография (UTF-8!)

common/
  data.tex          # управляющие переменные
  styles.tex        # пакеты и стили

parts/
  introduction.tex  # введение
  ...               # ... главы ...
  conclusion.tex    # заключение
  appendix_formatting.tex   # примеры форматирования

img/                # картинки
```

## Настройка проекта

Все переменные конфигурации сборки находятся в файле `data.tex`. Самые важные:

- `review`: по-умолчанию, `1`. Если установить в `0`, то все комментарии (`commentbox`), заметки (`\note`), задания (`\TODO`) и исправления (`\FIXME`) будут скрыты. Список замечаний печататься не будет. Кроме того, примеры форматирования (приложение А) также не будут добавлены в PDF.
- `showExamples`: по-умолчанию, `1`. Если установить в `0`, то примеры форматирования (приложение А) также не будут добавлены в PDF.

Автор: Вильмен Абрамян, vilmen.abramian@gmail.com

## English version

The text of a Master's thesis in Russian, written in LaTeX.

## 📂 Project Structure
The document is split into parts (chapters), each stored in a separate file. Style and package settings, as well as control variables, are also separated into dedicated files.

```
observe.tex         # main file
observe.bib         # bibliography (UTF-8!)

common/
  data.tex          # control variables
  styles.tex        # packages and styles

parts/
  introduction.tex  # introduction
  ...               # ... chapters ...
  conclusion.tex    # conclusion
  appendix_formatting.tex   # formatting examples

img/                # images
```

## ⚙️ Project Configuration
All build configuration variables are defined in `data.tex`. The most important ones:
- `review`: default is `1`. If set to `0`, all comments (`commentbox`), notes (`\note`), tasks (`\TODO`), and corrections (`\FIXME`) will be hidden. The list of remarks will not be printed, and formatting examples (Appendix A) will also be excluded from the PDF.
- `showExamples`: default is `1`. If set to `0`, the formatting examples (Appendix A) will not be included in the PDF either.

Author: Vilmen Abramian, vilmen.abramian@gmail.com
