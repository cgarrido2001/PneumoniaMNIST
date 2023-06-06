# PneumoniaMNIST

This is a proyect about using Pre-trained models with the objective to predict Pneumonia on Xrays.

Use python3.11



mejores modelos loss (validation):
1) ResNet50_ft_validation (0.0865)
2) VGG16_freezed_validation (0.0807)
3) VGG16_ft_validation (0.1025)
4) ResNet50_freezed_validation (0.106)


mejores modelos Accuracy (validation):

1) VGG16_freezzed_validation (0.9733)
2) ResNet50_ft_validation (0.9685)
3) VGG16_ft_validation (0.9637)
4) ResNet50_freezed_validation (0.9618)


mejores modelos Recall (Validation):

1) VGG16_freezed_validation (0.9835)
2) ResNet50_freezed_validation (0.9848)
3) VGG16_ft_validation (0.9674)
4) Resnet50_ft_validation (0.9737)




*Ranking*

1) VGG16_freezed_validation: Se clasifica como el mejor modelo ya que tiene el menor valor de loss, la mayor precisión (accuracy) y el mayor recall.

2) ResNet50_ft_validation: Se clasifica en segundo lugar debido a su buen rendimiento en términos de loss y accuracy, aunque su recall es ligeramente menor que el primer modelo.

3) VGG16_ft_validation: Se posiciona en tercer lugar, ya que tiene un valor de loss y accuracy inferiores a los modelos anteriores, aunque su recall es aceptable.

4) ResNet50_freezed_validation: Se clasifica en último lugar, ya que tiene el mayor valor de loss y su rendimiento en términos de accuracy y recall es inferior a los otros modelos.
