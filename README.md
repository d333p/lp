# lp - learn process

## That repo is for learning BCI and deep learning techniques.

В этом репозитории мы будем фиксировать:

1. список литературы и то, что читаем с комментариями, 
2. то, на что ссылаемся,
3. где лежит код, который используем,
4. где лежат данные, которые используем,
5. где лежит наш код и мануал к нему.
6. описание получающихся результатов,
7. цели, текущие задачи
8. TODO list с ориентировочными дедлайными, с которыми сами синхронизовываемся

В каждой именной папке внутри репа необходимо с одной стороны коротко, с другой стороны ёмко стараться рефлексировать над прочитанным материалом. Хороший пример лежит [здесь](https://github.com/aleju/papers). Много материала по DL лежит [здесь](https://github.com/ChristosChristofidis/awesome-deep-learning). [Пара](https://github.com/sheuan/Neural-Networks-on-Silicon) [вариантов](https://github.com/shaoxiaohu/CVPR2016) оформления ссылок на литературу. 

## Trick to know:

1. [TODO] описать tips&tricks которые нужно знать
2. фиксируйте вопросы, которые возникают в процессе

## Таня.

### theme (предварительная)

~ keywords: мки. ээг. классификация. состояния. анализ сигналов.

### lit
### links
### shared code
### data
### my code
### results
### purposes, targets
### TODO
* Added by Yura. 2016/12/05:
    * [ ] оформить свой реп
    * [ ] add пару статей по теме BCI и ЭЭГ процессингу, включая HOTSAX
    * [ ] внимательно посмотреть раздел Артёма
	* [ ] скачать WinEEG и перегнать файл .eeg в .txt либо .edf
	* [ ] see результаты https://github.com/sstober/ismir2016-brainbeats
	* [ ] полистать результаты Стобера https://goo.gl/dzsujC
	* [ ] интересно ли http://ir.lib.uwo.ca/etd/3769/ ?
	* [ ] сформулировать себе пару задач

## Коля.

### theme (предварительная)

~ keywords: глубокое обучение/deeplearning, видео/video, коррекция/correction, фильтрация/filtration

### lit

1. [Perceptual Losses for Real-Time Style Transfer and Super-Resolution, 2016: Johnson, Alahi](http://arxiv.org/abs/1603.08155)
    * added 2016/12/05
    * Department of Computer Science, Stanford University

2. [Real-Time Super-Resolution Using Efficient Sub-Pixel Convolution, 2016: Shi, Caballero](https://arxiv.org/abs/1609.05158)
    * added 2016/12/05
	* Twitter

3. [Deeply-Recursive Convolutional Network for Image Super-Resolution, 2016: Jiwon Kim, Jung Kwon Lee ](https://arxiv.org/abs/1511.04491)
    * added 2016/12/05
	* Department of ECE, ASRI, Seoul National University, Korea

4. [Photo-Realistic Super-Resolution Using a Generative Adversarial Network, 2016: Ledig, Theis](https://arxiv.org/abs/1609.04802)
    * added 2016/12/05
	* Twitter

### links
* [in TJournal: Почти как в сериалах: разработчик научил нейросеть улучшать качество фото низкого разрешения](https://tjournal.ru/36647-pochti-kak-v-serialah-razrabotchik-nauchil-neiroset-uluchshat-kachestvo-foto-nizkogo-razresheniya)

### shared code
* [Neural Enhance: increase the resolution of your photos using DL](https://github.com/alexjc/neural-enhance)

### data
### my code
### results
### purposes, targets
### TODO
* Added by Yura. 2016/12/05:
    * [ ] оформить свой реп
    * [ ] add пару статей по теме deeplearn, желательно Le Cun
    * [ ] add пару статей или манов по фильтрации видео use deeplearn
	* [ ] начать читать
	* [ ] запустить пример
	* [ ] сформулировать себе пару задач

## Артём.

### theme (предварительная)

~ Тема: определение ВП в ЕЕГ по одному предъявлению стимула. Пусть это будет визуальный стимул.
~ keywords: глубокое обучение/deeplearning, мки/bci, ээг/eeg, вызванные потенциалы/event releated potentials

### lit

1. [Deep Feature Learning for EEG Recordings, 2015: Stober, Sternin](https://arxiv.org/abs/1511.04306)
    * added 2016/12/05
    * The Brain and Mind Institute, University of Western Ontario, London, ON, Canada

2. [Best practice for single-trial detection of event-related potentials: Application to brain-computer interfaces, 2016: Cecotti, Reis](https://www.ncbi.nlm.nih.gov/pubmed/27453051)
    * added 2016/12/05
	* Faculty of Computing and Engineering, Ulster University, Magee campus, Londonderry, Northern Ireland, UK
	
	  Human Research and Engineering Directorate, US Army Research Laboratory, Aberdeen Proving Ground, USA

3. [BRAIN BEATS: TEMPO EXTRACTION FROM EEG DATA](http://bib.sebastianstober.de/ismir2016.pdf)(https://goo.gl/SuG3jf)
    * added 2016/12/05
	* [TODO] оформить

4. [Convolutional Neural Networks for P300 Detection with Application to Brain-Computer Interfaces, 2016: Ledig, Theis](http://uir.ulster.ac.uk/27675/1/cecotti_pami.pdf)
    * added 2016/12/05
	

### links

* [Победа алгоритмов DL в BCI конкурсе](https://news.developer.nvidia.com/imperial-college-leveraging-deep-learning-in-cybathlons-brain-computer-interface-race/)

### shared code
### data
### my code
### results
### purposes, targets
### TODO
* Added by Yura. 2016/12/05:
    * [ ] почитать про P300 ERP
    * [ ] посмотреть https://www.youtube.com/watch?v=-50fVNjm_2Y
    * [ ] Шишкина https://www.youtube.com/watch?v=mSWoXrig2oM
    * [ ] https://www.youtube.com/watch?v=mSWoXrig2oM
    * [ ] https://www.youtube.com/watch?v=4LCkDwcXMHE 
    * [ ] найти авторов победителей конкурса по BCI
    * [ ] скачать WinEEG
    * [ ] поискать на гитхабе проекты по eeg + deep learning
	* [ ] найти интересных соавторов Stuberа https://goo.gl/dzsujC
	* [ ] выписать заинтересовавшие статьи из https://goo.gl/UJt4CL
	* [ ] сформулировать себе пару задач