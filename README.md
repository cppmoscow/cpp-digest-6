# cpp-digest-6

Название: C++ Дайджест №5 (16 октября – 29 октября 2023) 

Теги: дайджест, c++-дайджест, c++

Хабы: Программирование, C++

## Аннотация

Привет, Хабр! Сегодня я хочу вам представить подборку интересных новостей и материалов из мира C++ за последние две недели.

Приятного чтения!

## 📝 Статьи

1. Habr: 🇷🇺 [Опыт создания UI библиотеки на C++](https://habr.com/ru/articles/768336/) — Общий обзор архитектуры самописной кроссплатформенной UI-библиотеки.
2. Habr: 🇷🇺 [FreeCAD и C++ код с неопределённым поведением для медитации](https://habr.com/ru/companies/pvs-studio/articles/768388/), [Опечатки, нулевые указатели и коварный таб: 33 фрагмента в библиотеке GTK](https://habr.com/ru/companies/pvs-studio/articles/770050/) — Разбор ошибок, найденных в кодовой базе [FreeCAD](https://github.com/FreeCAD/FreeCAD) и [GTK](https://github.com/GNOME/gtk) с помощью [PVS-Studio](https://pvs-studio.com/en/pvs-studio/).
3. Habr: 🇷🇺 [Показываем видео в терминале](https://habr.com/ru/articles/768456/) — Знакомство с библиотекой OpenCV на примере рисования видео в терминале.
4. Habr: 🇷🇺 [Инженерный калькулятор на C++. Часть 1: Токенизатор математических выражений](https://habr.com/ru/articles/769812/) — Пример реализации лексического анализатора для математический выражений с кратким введением в теорию конечных автоматов.
5. Habr: 🇷🇺 [Пишем свой QTableView с нуля](https://habr.com/ru/articles/761530/)
6. Habr: 🇷🇺 [Как и зачем мы парсим XML](https://habr.com/ru/companies/tensor/articles/769722/) — О различных подходах к парсингу XML и их производительности.
7. Habr: 🇷🇺 [Backend Driven UI с точки зрения бэкенда: к чему готовиться, если вы решили на него перейти](https://habr.com/ru/companies/yandex/articles/768282/)
8. Habr: 🇷🇺 [Детекция машин на мобилке в 2023. С какими проблемами мы столкнулись и как решали](https://habr.com/ru/companies/raft/articles/770302/) — Обзор решения для детекции автомобилей на мобильном устройстве в режиме реального времени, разработанного на C++ с использованием [TensorFlow-Lite](https://www.tensorflow.org/lite) и [Qt](https://www.qt.io/).
9. Conan: [C++ Modules: The Packaging](https://blog.conan.io/2023/10/17/modules-the-packaging-story.html) — Традиционный пакет conan включает в себя собственно бинарник (.so, .a) и заголовочные файлы. Но с C++20 в языке появились модули, как нам «упаковывать» их, и возможно ли сделать это кроссплатформенно?
10. Daniel Lemire: [For processing strings, streams in C++ can be slow](https://lemire.me/blog/2023/10/19/for-processing-strings-streams-in-c-can-be-slow/) — Бенчмарк: насколько плохи I/O streams?
11. Marco Arena: [SObjectizer Tales — 2: Can you call me back?](https://marcoarena.wordpress.com/2023/10/19/sobjectizer-tales-2/), [SObjectizer Tales – 3: Acquisition loop](https://marcoarena.wordpress.com/2023/10/26/sobjectizer-tales-3/) — Продолжение серии статей, посвященной построению программ на основе акторной модели с помощью [SObjectizer](https://github.com/Stiffstream/sobjectizer): интеграция колбэков в producer agents, message passing style.
12. Sandor Dargo: [My battle against different signedness comparisons: the most usual violations](https://www.sandordargo.com/blog/2023/10/18/signed-unsigned-comparison-the-most-usual-violations), [the worst violations](https://www.sandordargo.com/blog/2023/10/25/signed-unsigned-comparison-the-worst-violations) — О наиболее распространненых и коварных ошибках при сравнении знаковых и беззнаковых целых чисел.
13. JeanHeyd Meneide: [Implementing #embed for C and C++](https://thephd.dev/implementing-embed-c-and-c++) — История реализации [директивы бинарного включения данных](https://en.cppreference.com/w/c/preprocessor/embed) в gcc и clang для C и C++.
14. Bartłomiej Filipek: [How to use std::span from C++20](https://www.cppstories.com/2023/span-cpp20/) — О том, что такое [std::span](https://en.cppreference.com/w/cpp/container/span) (C++20) и как он может упростить ваш код.
15. Conan: [Conan launches metadata files management](https://blog.conan.io/2023/10/24/Conan-launches-metadata-files.html) — О распространении метаданных с помощью conan.
16. Raymond Chen: [How do I add a non-copyable, non-movable object to a std::map or std::unordered_map?](https://devblogs.microsoft.com/oldnewthing/20231023-00/?p=108916) — О том, как мы можем поместить некопируемый неперемещаемый объект в ассоциативный контейнер.
   
## 📺 Видео и доклады

1. Jason Turner: [C++ Weekly — Ep 398 — C++23's zip_view](https://www.youtube.com/watch?v=MVXGdwREo_E), [C++ Weekly — Ep 399 — C++23's slide_view vs adjacent_view](https://www.youtube.com/watch?v=czmGjH16Hb0) — Обзор нововведений C++23: [zip_view](https://en.cppreference.com/w/cpp/ranges/zip_view), [slide_view](https://en.cppreference.com/w/cpp/ranges/slide_view) и [adjacent_view](https://en.cppreference.com/w/cpp/ranges/adjacent_view).

## 🎙️ Подкасты

1. CppCast: [Episode 370, Physical Units & System of Quantities](https://cppcast.com/physical_units_and_a_system_of_quantities/) — О библиотеке [mp-units](https://github.com/mpusz/mp-units), кандидате на включение в C++29 (связанные пропозалы: [P1935](https://wg21.link/p1935), [P2980](https://wg21.link/p2980), [P2981](https://wg21.link/p2981), [P2982](https://wg21.link/p2982))
 
## Послесловие

> Дайджест составлен и опубликован при поддержке московского сообщества программистов [C++ Moscow](https://t.me/cppmoscow_info)

Заметили ошибку или опечатку? Сообщите в личку ([telegram](https://t.me/eoanermine), [habr](https://habr.com/ru/conversations/eoanermine/))

Прислать ссылку можно [через форму](https://forms.yandex.ru/cloud/64f48043e010db921819c447/) или просто написав мне в личные сообщения ([telegram](https://t.me/eoanermine), [habr](https://habr.com/ru/conversations/eoanermine/))

← Предыдущий выпуск: [C++ Дайджест №6](https://habr.com/ru/articles/767818/)
