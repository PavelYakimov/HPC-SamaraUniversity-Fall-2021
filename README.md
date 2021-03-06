# HPC-SamaraUniversity-Fall-2021
Настоящий курс по дисциплине "Высокопроизводительные и облачные вычисления" предназначен для студентов магистерской программы ПМИ Самарского университета, осенний семестр 2020.

Лектор: [Якимов Павел Юрьевич](https://ssau.ru/staff/222993132-yakimov-pavel-yurevich) - доцент кафедры суперкомьютеров и общей информатики, к.т.н.

При подготовке курса были использованы следующие материалы:
- [NVIDIA CUDA C++ Programming Guide](https://docs.nvidia.com/cuda/cuda-c-programming-guide/index.html)
- [CUDA C++ Best Practices Guide](https://docs.nvidia.com/cuda/cuda-c-best-practices-guide/index.html)
- Материалы компании Applied Parallel Computing LLC
- Наработки автора

# Лекции

Здесь представлены слайды для презентаций, которые демонстрировались во время лекций:
- [1. Introduction to CUDA](/slides/1_en_Introduction.pdf)
- [2. CUDA Memory](/slides/2_en_Memory.pdf)
- [3. CUDA libraries](/slides/3_libraries.pdf)
- [4. Thrust library](/slides/4_thrust.pdf)
- [5. Multi-GPU](/slides/5_mpgu_compressed.pdf)
- [6. PyCUDA](/slides/6_pycuda-ru.pdf)
- [7. Profiling](/slides/7_Profiling.pdf)

Записи лекций:
- Лекция 1. Introduction to CUDA (Part 1): [Презентация](https://github.com/PavelYakimov/HPC-SamaraUniversity-Fall-2021/files/7186648/en_Introduction.pdf), [Ссылка на запись](https://1drv.ms/v/s!AvM8VWt8XD6Kic0Q7m5IUl0N-tMHEg?e=aAitt5)
- Лекция 2. Introduction to CUDA (Part 2): [Ссылка на запись](https://1drv.ms/v/s!AvM8VWt8XD6Kic8zxiauCTQG-zND0w?e=uadl1C), 
- Лекция 3. CUDA Memory [Ссылка на запись](https://1drv.ms/v/s!AvM8VWt8XD6KidRART5hsicj_ZGdyQ?e=BUPy5D),
- Лекция 4. Thrust. [Ссылка на запись](https://1drv.ms/v/s!AvM8VWt8XD6KidYgTHi0CpUWOqSOdA?e=coReZG),
- Лекция 5. CUDA Math Libraries. [Part 1 (смотреть с 45:00)](https://bbb.ssau.ru/playback/presentation/2.0/playback.html?meetingId=b76cc06c5f576c9314c26c033cc5df63fbd1269f-1601888085737); [Part 2](https://bbb.ssau.ru/playback/presentation/2.0/playback.html?meetingId=b76cc06c5f576c9314c26c033cc5df63fbd1269f-1602659393598)
- Лекция 6. Multi-GPU [Ссылка на запись](https://1drv.ms/v/s!AvM8VWt8XD6Kieswpbv7YNqdCxwLVw?e=aTayPu),
- Лекция 7, _Optional_. Python + CUDA [Ссылка на запись](https://bbb.ssau.ru/playback/presentation/2.0/playback.html?meetingId=b76cc06c5f576c9314c26c033cc5df63fbd1269f-1606302273155)

# Лабораторные работы

[Ссылка в Google Drive на таблицу с результатами по лабораторным работам](https://docs.google.com/spreadsheets/d/1_QScXE8Q8pl-AKluKXKhohZs7qSEeeJqVZ8JmRk6n9k/edit?usp=sharing)

1. [Matrix Multiplication, 0 points](https://github.com/PavelYakimov/HPC-SamaraUniversity-Fall-2021/files/7152853/Lab0_MatMul.pdf)
2. [VectorSum.pdf, 1 point](https://github.com/PavelYakimov/HPC-SamaraUniversity-Fall-2021/files/7153431/Lab1_VectorSum.pdf)
3. [Bilateral Filtering, 2 points](https://github.com/PavelYakimov/HPC-SamaraUniversity-Fall-2021/blob/main/bilateral.pdf)
4. [Bilinear Interpolation, 1 point](https://github.com/PavelYakimov/HPC-SamaraUniversity-Fall-2021/blob/main/bilinear_interpolation.pdf)
5. [Genetic Algorithm, 3 points](https://github.com/PavelYakimov/HPC-SamaraUniversity-Fall-2021/blob/main/genetic_algorithm.pdf)
6. [Harris Detector, 2 points](https://github.com/PavelYakimov/HPC-SamaraUniversity-Fall-2021/blob/main/harris_algorithm.pdf)
7. [Substrings Search, 2 points](https://github.com/PavelYakimov/HPC-SamaraUniversity-Fall-2021/blob/main/mass_search.pdf)
8. [Pi-value Calculation, 1 point](https://github.com/PavelYakimov/HPC-SamaraUniversity-Fall-2021/blob/main/pi_monte_carlo.pdf)
9. [Ray Tracing, 4 points](https://github.com/PavelYakimov/HPC-SamaraUniversity-Fall-2021/blob/main/ray_tracing.pdf)
10. [Salt and Pepper, 2 points](https://github.com/PavelYakimov/HPC-SamaraUniversity-Fall-2021/blob/main/salt_and_pepper.pdf)
11. [Spectrogram, 2.5 points](https://github.com/PavelYakimov/HPC-SamaraUniversity-Fall-2021/blob/main/spectrogram.pdf)
12. Compare Intel GPU vs Nvidia GPU (please, refer to the lecturer), 3 points
13. Custom Task, 1-9 points (depends on the complexity of the provided task)

[Ссылка на запись "инструкции" доступа по ssh](https://1drv.ms/v/s!AvM8VWt8XD6Kic42dl9NF3nUOK1iiA?e=Wv6WGQ)

# Сценарий проведения зачета

Зачет будет проходить 11.01.2021 в 10:00 с использоанием Zoom.

Вначале вам необходимо подключиться в Zoom: ﻿Pavel Yakimov приглашает вас на запланированную конференцию: Zoom.

Тема: Зачет HPC, ПМИ 613X
Время: 11 янв. 2022 10:00 AM Дубай

Подключиться к конференции Zoom: https://zoom.us/j/8806326199?pwd=eEhaTVFPYTJHeVExakdNaHl0ZFpVQT09 (Идентификатор конференции: 880 632 6199, Код доступа: 6zzyUR). Там будет вся оперативная информация, там же появится ссылка на тест.

Зачет состоит из двух частей.

### Прохождение теста

Ссылка на тест будет предоставлена в самом начале зачета. Прохождение теста должно занять у вас не более 60 минут. Тест состоит из вопросов по материалам лекций + задачи в виде: “вот код, какой ответ?”. 
Настоятельно прошу максимально не пользоваться ничем, кроме того, что сами уже знаете.

Как только заканчиваете тест, пишите об этом в чате bbb.

### Собеседование

Собеседование будет проходить с каждым по отдельности. Очередность собеседуемых будет определяться в основном треде зачета или в соответствии с тем, как будут приходить результаты теста.

В целом необходим только микрофон. Но легче общаться всё-таки с включенной камерой.

Во время собеседования сначала разберем ответы на вопросы теста.
Потом посмотрим на лабораторные работы и обсудим некоторые моменты в коде. Без лабораторных работ оценка за зачет выставлена не будет!

### Список вопросов

В целом обсуждать будем всё то, что было в лекциях (смотри раздел лекции).
Вопросы следующие:
1. Введение в параллельные вычисления. Пути достижения параллелизма. Классификация компьютерных систем. Характеристики схем коммуникации в многопроцессорных вычислительных систем. Высокопроизводительный вычислительный кластер СГАУ.
2. Производительность и параллелизм. Эволюция GPGPU. SIMD и SIMT, аппаратная архитектура GPU NVIDIA. Комплекс программного обеспечения CUDA Toolkit.Модель программирования CUDA: Основные принципы. Взаимодействие процессора и GPU. CUDA Сетка.
3. Уровни памяти (обзор). Глобальная память.
4. CUDA. Регистры, локальная память.
5. CUDA. Общая память. Постоянная память. Текстурная память.
6. CUDA. Реализация стандартных алгоритмов на GPU: Умножение матриц. Редукция.
7. CURAND, CUBLAS, CUSPARSE, CUFFT.
8. GPU программирование с использованием Thrust. Линейные преобразования и функторы. Заполнители и кортежи. Производительность. Взаимодействие с CUDA / С. Прикладные библиотеки.
9. Multi-GPU. Способы организации работы на нескольких GPU.

### UPD: Дополнительный день зачета

Для тех, кто по той или иной уважительной причине не сможет 11.01.2022 сдавать зачет, просьба написать мне об этом на yakimov@ssau.ru . Будет возможность сдать зачет 19.01.2022 в 18:00.

Ссылка для доплнительного дня:

Pavel Yakimov приглашает вас на запланированную конференцию: Zoom.

Тема: 19.01.2022 - Зачет HPC - Step 2
Время: 19 янв. 2022 06:00 PM Дубай

Подключиться к конференции Zoom
https://zoom.us/j/95736057255?pwd=dGg4OUtLYTFMZnp3b25tK1o5VXZQUT09

Идентификатор конференции: 957 3605 7255
Код доступа: 078137


 
