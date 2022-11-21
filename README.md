# IHW2_bioinformatics
Индивидуальное задание 2 по биоинформатике
## Бесшапов Алексей, группа 2, выбранный ген: Ribosomal protein L12
### Представлены виды (представители):
- human (homo sapiens) - человек
- primates (macaca mulatta) - макака
- mouse (mus musculus) - домовая мышь
- rat (rattus norvegicus) - серая крыса
- bovine (bos taurus) - тур
- marsupials (phascolarctos cinereus) - коала
- snake (protobothrops mucrosquamatus) - гадюка
- lizard (lacerta agilis) - прыткая ящерица
- turtle (chelonia mydas) - зеленая черепаха
- bird (accipiter gentilis) - ястреб-тетеревятник
- fish (pygocentrus nattereri) - пиранья
- plant (dendrobium catenatum) - дендробиум цепочечный
- fungi (saccharomyces cerevisiae) - дрожжи пекарские
- archaea (sulfolobus sp. A20-N-F6)
- bacteria (vibrio cholerae) - холерный вибрион
### Множественное выравнивание
Проводим выравнивание последовательностей с использованием алгоритмов clustalW и muscle. Результаты выравниваний:
- ClustalW:
<img width="958" alt="ribosomal_protein_L12_clustalW" src="https://user-images.githubusercontent.com/45789410/203174434-37b01242-54f2-4b7f-908f-85beece2b2e0.png">

- Muscle:
<img width="958" alt="ribosomal_protein_L12_muscle" src="https://user-images.githubusercontent.com/45789410/203174503-60937386-a63f-4da2-a9c3-97c59c7547b6.png">

#### Заметим, что результаты выравниваний отличаются.

### Построение филогенетических деревьев
Строим филогенетические деревья с использованием алгоритмов UPGMA, neighbor joining, maximum likelihood для обоих выравниваний, полученных на предыдущем этапе.
- UPGMA:
  - clustalW:
  <img width="745" alt="ribosomal_protein_L12_clustalW_UPGMA" src="https://user-images.githubusercontent.com/45789410/203175503-84a7e5fc-3885-45d9-8f97-83ee78cba549.png">
  
  - muscle:
  <img width="701" alt="ribosomal_protein_L12_muscle_UPGMA" src="https://user-images.githubusercontent.com/45789410/203175585-2ca20f32-2a3e-4b0a-8d67-026a03fdb617.png">
  
- NJ:
  - clustalW:
  <img width="706" alt="ribosomal_protein_L12_clustalW_NJ" src="https://user-images.githubusercontent.com/45789410/203175779-c63d1530-300e-4835-b7c5-d26d9698218d.png">
  
  - muscle:
  <img width="696" alt="ribosomal_protein_L12_muscle_NJ" src="https://user-images.githubusercontent.com/45789410/203175814-da4f70fd-98e0-4332-aea6-14a59c9e84ba.png">

- ML:
  - clustalW:
  <img width="703" alt="ribosomal_protein_L12_clustalW_ML" src="https://user-images.githubusercontent.com/45789410/203175866-d0a8fd45-6c6b-4eb3-9a0f-7c59b4103eba.png">
  
  - muscle:
  <img width="697" alt="ribosomal_protein_L12_muscle_ML" src="https://user-images.githubusercontent.com/45789410/203175904-3677e3d2-85a4-4426-8c9e-325912848264.png">

### Выводы
1. Лучше отработал алгоритм выравнивания Muscle, так как данный метод проводит выравнивание и глобально, и локально
2. Топология деревьев при построении разными методами различается
3. Бутстрэп-значения различные
4. Деревья обильно не совпадают с принятыми деревьями видов
