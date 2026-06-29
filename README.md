<!-- BANNER: замени ссылку на своё изображение (рекомендуемый размер: 1500×500px) -->
<!-- Создай баннер на https://www.canva.com или https://www.figma.com -->
<!-- Сохрани файл как banner.png в корне репозитория и раскомментируй строку ниже -->
<!-- <img src="./banner.png" width="100%" alt="Тимур Билалов"/> -->

<!-- Временный баннер — работает сразу без файла. Замени на своё фото/арт выше -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00599C,100:0d1117&height=200&section=header&text=Тимур%20Билалов&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=C%2B%2B%20Systems%20Engineer%20%7C%20ITMO%20University&descAlignY=60&descSize=18&descColor=8b949e" width="100%"/>

<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=3000&pause=800&color=00599C&center=true&vCenter=true&width=650&lines=C%2B%2B20%2F23+%7C+Low-level+%7C+Hardware;Competitive+Programmer+%7C+ITMO+University;Building+things+compilers+understand" alt="Typing SVG" />
</a>

<p>
  <a href="https://t.me/X_xpoint">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/>
  </a>
  <a href="mailto:timurbilalov14@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://codeforces.com/profile/X_xp">
    <img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white"/>
  </a>
</p>

</div>

---

## `whoami`

```cpp
#include <developer.hpp>
#include <future>

int main() {
    auto timur = Developer {
        .name       = "Тимур Билалов",
        .location   = "Санкт-Петербург",
        .university = "ITMO University — FITiP",
        // ICPC 2025 Quarter-Finalist
        // 2× Absolute Regional Champion — Olympiad in Informatics
        // Yandex Algorithm School graduate
    };

    timur.set_core_stack({ "C++20/23", "CMake", "Git", "Linux/Arch" });
    timur.set_hardware({ "Verilog", "Logisim", "RISC-V" });

    static_assert(timur.cp_experience() >= 5_years, "underfitted");

    while (alive) {
        timur.push_to_main(timur.build_something_unusual());
    }
}
```

---

## 🔧 Стек

<div align="center">

**Языки**

![C++](https://img.shields.io/badge/C++23-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-FF6600?style=flat-square&logo=ieee&logoColor=white)

**Инфраструктура**

![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_(Arch)-1793D1?style=flat-square&logo=archlinux&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Тестирование**

![GTest](https://img.shields.io/badge/GTest%2FGMock-4285F4?style=flat-square&logo=google&logoColor=white)

</div>

---

## Проекты

> Репозитории открываются по мере готовности к публикации — часть кода ещё в работе.

---

### Task Orchestrator
`C++23` `async` `coroutines` `fault-tolerance`

Библиотека для построения графов вычислений. Не просто threadpool — runtime с политиками: кэширование, внешние очереди, batch-execution, восстановление после отказов и live-tracking состояний задач без остановки графа.

---

### Lazy Range Library
`C++20` `zero-overhead` `iterators` `concepts`

Собственная range-библиотека с упором на ленивость и O(1) памяти. Не STL, не ranges-v3 — своя семантика, свои sentinel'ы и тег-система для типобезопасного расширения. `mmap`-итератор с forward-категорией в обход потоковых ограничений.

---

### Valkey-совместимая БД с векторизацией
`C++` `in-memory` `database` `SIMD`

Кастомное in-memory хранилище, совместимое с протоколом Valkey, с поддержкой векторных операций.

---

### RISC-V Дизассемблер
`C++` `ELF` `RISC-V` `binary`

ELF → RISC-V asm. Разбор машинного кода в читаемый ассемблер без сторонних библиотек — понимание ISA изнутри.

---

### Load Balancing Benchmark
`C++23` `Asio` `coroutines` `JSON` `benchmarking`

Инструмент сравнения алгоритмов балансировки нагрузки в многопоточной среде на асинхронных корутинах. Настраиваемые сценарии, JSON-отчёты с детальной статистикой по латентности, отказам и распределению. Веб-визуализация результатов.

---

### Параметризуемый float
`C++` `Verilog` `hardware` `IEEE 754`

Реализация параметризуемого формата с плавающей точкой (e4m3fn / e5m2 / half / double) на C++ и Verilog. Полный тестбенч, статистика точности.

---

### Другие проекты

| Проект | Стек | Описание |
|---|---|---|
| **Музыкальный язык + интерпретатор** | `C++` `AST` `DSP` | Собственный язык с нотами, инструментами, эффектами и функциями. Компилятор дерева разбора в WAV |
| **Парсер JSON** | `C++` | С подстановкой параметров и шаблонами |
| **Архиватор Хаффмана** | `C++` | Подключаемые схемы кодирования |
| **Сервис фильтрации билетов** | `C++20` `REST` `FTXUI` | Внешний API + кэш запросов + TUI-интерфейс |
| **Модель кэша** | `Verilog` `LRU` | LRU / bpLRU, статистика попаданий, testbench |
| **Blowfish** | `Logisim` | Аппаратная реализация алгоритма шифрования |

---

## Competitive Programming

<!-- Codeforces статистика — вставь свой handle ниже -->
<!-- Сервис: https://codeforces-readme-stats.vercel.app -->
<!-- Замени X_xp на свой CF handle если отличается -->

<div align="center">

<a href="https://codeforces.com/profile/X_xp">
  <img src="https://codeforces-readme-stats.vercel.app/api/card?username=X_xp&theme=dark&force_username=true" alt="Codeforces Stats"/>
</a>

<!-- Если карточка выше не работает — раскомментируй строки ниже и используй альтернативу -->
<!--
<img src="https://cf.leed.at?id=X_xp" alt="Codeforces rating"/>
-->

</div>

```
ICPC 2025          — Четвертьфиналист
ВсОШ по информатике — Дважды абсолютный победитель региона
Yandex School      — Алгоритмы (выпускник)
Codeforces         — profile/X_xp
```

---

## GitHub Stats

<!-- github-readme-stats иногда нестабилен. Если не грузится — попробуй альтернативы ниже -->

<div align="center">

<!-- Если не работает — раскомментируй этот блок (альтернативный сервис) -->
<img src="https://streak-stats.demolab.com?user=Xx5830&theme=tokyonight&hide_border=true" />

</div>

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00599C,100:0d1117&height=100&section=footer" width="100%"/>
