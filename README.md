# pytorch_transfer_learning

 Данный репозиторий является выполнением семинара на курсе от МФТИ:

 https://www.youtube.com/watch?v=4AUxDH4doV0&list=PL0Ks75aof3Tiru-UvOvYmXzD1tU0NrR8V&index=46

 Датасет можно взять отсюда:
 
 https://download.pytorch.org/tutorial/hymenoptera_data.zip

 Реализованы:
  1. def imshow - визуализация изображения с обратной нормализацией.
  2. def train_model - train loop + model validation, save best params.
  3. def visualize_model - визуализация предсказаний модели.
  4. def evaluate - оценка модели по метрике accuracy.
  5. model_ft - использование pre-train resnet18 без изменений.
  6. model_conv - использование pre-train resnet18 в качестве feature extractor.
  7. model_mixed_lr - использование pre-train resnet18 с разным LR для разных слоев сети.
  8. eff_model - использование pre-train efficientnet_b0 в качестве feature extractor.
  9. fine_tune_eff_model - fine-tune efficientnet_b0.
