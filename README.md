
# alaska2-image-steganalysis 
- код решения 69 места (бронза) 

## Описание решения
* Модель: efficientnet-b4
* Аугментации: HorizontalFlip, VerticalFlip
* Лосс: CrossEntropyLoss
* Оптимизатор: AdamW
* Scheduler: CosineAnnealingLR
* Метрика: WAUC
* TTA: D4

## HOW TO RUN
Весь пайплайн находится в файле Alaska2_notebook.ipynb


### Железо/время тренировки

Модель тренеровалась на 1 x TeslaV100.
Модель обучалась 150 эпох до сабмита (~4 дня) (~ 96 GPU часов) 

