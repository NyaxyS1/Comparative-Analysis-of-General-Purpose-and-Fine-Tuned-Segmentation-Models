# Comparative-Analysis-of-General-Purpose-and-Fine-Tuned-Segmentation-Models
UNet vs SAM/Mask2Former: benchmark of fine-tuned vs zero-shot segmentation. Metrics: IoU, Dice, FPS.

## 📌 Описание
Сравнение моделей сегментации:
- **Fine-tuned**: U-Net (обучен на датасете дорог)
- **General-purpose**: SAM (Segment Anything Model, zero-shot)

## 📁 Содержимое
- `Unet` — обучение U-Net и реализация на двух датасетах
- `SAM` — Реализация SAM

## 🖼️ Результаты
Обе модели сегментации показали достойные результаты, но оценить их математически относительно друг друга не представляется возможным, так как SAM создает слишком большое количество масок, не предусмотренных выбранным датасетом
## 📊 Итоговое сравнение
| Модель | IoU |
|--------|------|
| SAM (zero-shot) | |
| Fine-tuned U-Net | 0.95 |
