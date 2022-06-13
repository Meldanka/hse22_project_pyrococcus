# hse22_project_pyrococcus

* Google colab https://colab.research.google.com/drive/1TL4SnCnUJ-ginrje5i1uSEClQTsUS-Ju?usp=sharing

* Будем анализировать 5 геномов архей pyrococcus
* Общая информация: экстратермофильный вид архей, один из немногих организмов, содержащих вольфрам в составе ферментов.

<img width="512" alt="Снимок экрана 2022-06-09 в 03 03 55" src="https://user-images.githubusercontent.com/91221560/172737261-f5d44b7b-391c-4e4b-91a2-2d0ace8103ff.png">

* Выбирала с достаточно большим содержанием GC%, у всех assembly level complete:
<img width="403" alt="Снимок экрана 2022-06-09 в 02 59 37" src="https://user-images.githubusercontent.com/91221560/172737358-a7f2ca2d-0ab1-4600-b672-4d94e3651f53.png">

* Проанализировала аннотированные гены и произвела работу zhunt, получились следующие результаты:
<img width="1056" alt="Снимок экрана 2022-06-09 в 02 59 51" src="https://user-images.githubusercontent.com/91221560/172737478-7f3f750b-f198-4477-b29d-17db412f3cb1.png">

* При отборе zhunt c большим скором чаще всего встречались последовательности "acg":
<img width="592" alt="Снимок экрана 2022-06-09 в 03 00 19" src="https://user-images.githubusercontent.com/91221560/172737600-3230b362-56d6-4637-a185-ae54b738416e.png">

* Получились следующие гистограммы:
<img width="392" alt="Снимок экрана 2022-06-09 в 03 00 55" src="https://user-images.githubusercontent.com/91221560/172737665-35dafed8-60c6-4d5b-a347-239cef29e881.png">
<img width="392" alt="Снимок экрана 2022-06-09 в 03 01 03" src="https://user-images.githubusercontent.com/91221560/172737672-7af3fd59-cc15-4b56-802c-f91d4fbdbb74.png">
<img width="392" alt="Снимок экрана 2022-06-09 в 03 01 11" src="https://user-images.githubusercontent.com/91221560/172737685-bb86a9c1-5c92-450e-9f70-8cdc27288a10.png">
<img width="392" alt="Снимок экрана 2022-06-09 в 03 01 18" src="https://user-images.githubusercontent.com/91221560/172737692-8ec7999f-8d97-4174-a546-14bb415e3fd7.png">
<img width="392" alt="Снимок экрана 2022-06-09 в 03 01 26" src="https://user-images.githubusercontent.com/91221560/172737704-deeb4db4-fa0f-4a0d-8b66-47cb2d4ecb96.png">

* Визуализируем предсказанные участки Z-DNA

<img width="899" alt="Снимок экрана 2022-06-12 в 18 23 03" src="https://user-images.githubusercontent.com/91221560/173240527-1ded2b0e-b4d6-41bf-9ac5-011ca3572531.png">
<img width="899" alt="Снимок экрана 2022-06-12 в 18 23 03" src="https://user-images.githubusercontent.com/91221560/173240533-0fcf4a11-554a-4cf9-8b7b-33395d3b2272.png">
<img width="1019" alt="Снимок экрана 2022-06-12 в 18 22 41" src="https://user-images.githubusercontent.com/91221560/173240538-5ac6f40f-e643-428f-8f7c-0eb4244a800c.png">

* С помощью программы proteinortho определяем гомологичные связи между белками выбранных геномов
* Гистограмма кластеров по кол-ву разных геномов в кластере:
<img width="496" alt="Снимок экрана 2022-06-12 в 16 37 02" src="https://user-images.githubusercontent.com/91221560/173240552-29a13246-a937-4792-8db2-43226dcf7bc3.png">

