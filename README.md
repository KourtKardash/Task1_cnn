# Task1_cnn
Задание было выполнено с использованием CNN. Обучение проводилось на наборе train_tiny, а тестирование - на наборе test_small. При произвольном выборе 10% данных из набора test_small точность предсказания - 0.9778, на всем наборе - 0.8783. На наборе test_tiny точность составляет 0.8778.
Из дополнительных заданий была реализована аугментация данных с помощью слоев, переворачивающих изображение по горизонтали и вертикали, вращающих изображение, а также регулирующих контраст (LBL11). Используется валидация данных с коэффициентом (0.3) (LBL1). На каждой эпохе обучения выводится значение функции потерь и точность (LBL5). А также после окончания обучения строится график зависимости значений функции потерь от номера эпохи и график зависимости точности предсказания от номера эпохи (LBL6).
