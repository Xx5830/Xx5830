<!-- ╔══════════════════════════════════════════════════════════════╗ -->
<!-- ║  БАННЕР: замени capsule-render на своё изображение          ║ -->
<!-- ║  1. Создай баннер (1500×400px) на canva.com или figma.com   ║ -->
<!-- ║  2. Положи файл banner.png в корень репозитория             ║ -->
<!-- ║  3. Замени <img> ниже на: <img src="./banner.png" width="100%"/> ║ -->
<!-- ╚══════════════════════════════════════════════════════════════╝ -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:0a1628,70:00599C,100:0d1117&height=220&section=header&text=Тимур%20Билалов&fontSize=56&fontColor=ffffff&fontAlignY=40&desc=C%2B%2B%20Systems%20Engineer%20%E2%80%94%20ITMO%20University&descAlignY=62&descSize=17&descColor=7aa2cc" width="100%"/>

<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=17&duration=3000&pause=900&color=00599C&center=true&vCenter=true&width=620&lines=C%2B%2B20%2F23+%7C+Low-level+%7C+Systems;Algorithms+%7C+Hardware+%7C+ITMO+University;Building+things+compilers+understand" alt="Typing SVG"/>
</a>

<br/>

<a href="https://t.me/X_xpoint"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/></a>
<a href="mailto:timurbilalov14@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://codeforces.com/profile/X_xp"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white"/></a>

</div>

---

## `whoami`

```cpp
#include <developer.hpp>

int main() {
    auto timur = Developer {
        .name       = "Тимур Билалов",
        .location   = "Санкт-Петербург",
        .university = "ITMO University - FITiP",
    };

    timur.set_focus({ "C++20/23", "systems programming", "hardware architecture" });

    // ICPC 2025 Quarter-Finalist
    // 2× Absolute Regional Champion - Olympiad in Informatics
    // Yandex Algorithm School - graduate
    static_assert(timur.cp_years() >= 5, "underfitted");

    while (alive) {
        timur.push_to_main(timur.build_something_unusual());
    }
}
```

---

## Стек

<div align="center">

**Языки**

![C++](https://img.shields.io/badge/C++_20%2F23-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-FF6600?style=for-the-badge&logo=ieee&logoColor=white)

**Инструменты**

![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=archlinux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![GTest](https://img.shields.io/badge/GTest%2FGMock-4285F4?style=for-the-badge&logo=google&logoColor=white)

**Аппаратное**

![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=for-the-badge&logo=riscv&logoColor=white)
![Logisim](https://img.shields.io/badge/Logisim-555555?style=for-the-badge&logoColor=white)

</div>

---

## Проекты

> Репозитории открываются по мере готовности - часть кода ещё в работе.

<br/>

**Task Orchestrator** - `C++23`

![async](https://img.shields.io/badge/async-0a3d62?style=flat-square)
![coroutines](https://img.shields.io/badge/coroutines-1a5276?style=flat-square)
![graphs](https://img.shields.io/badge/computation%20graphs-154360?style=flat-square)
![fault--tolerance](https://img.shields.io/badge/fault--tolerance-1b2631?style=flat-square)

Библиотека для построения графов вычислений. Не просто threadpool - runtime с политиками: кэширование, внешние очереди, batch-execution, восстановление после отказов и live-tracking состояний задач без остановки графа.

<br/>

**Lazy Range Library** - `C++20`

![zero-overhead](https://img.shields.io/badge/zero--overhead-1a3a00?style=flat-square)
![iterators](https://img.shields.io/badge/iterators-2d5a00?style=flat-square)
![concepts](https://img.shields.io/badge/concepts-3d7000?style=flat-square)
![O(1) memory](https://img.shields.io/badge/O(1)%20memory-4a8500?style=flat-square)

Собственная range-библиотека с упором на ленивость и O(1) памяти. Не STL, не ranges-v3 - своя семантика, свои sentinel'ы и тег-система для типобезопасного расширения. `mmap`-итератор с forward-категорией в обход потоковых ограничений.

<br/>

**Valkey-compatible DB + векторизация** - `C++`

![in-memory](https://img.shields.io/badge/in--memory-6d0000?style=flat-square)
![database](https://img.shields.io/badge/database-8b0000?style=flat-square)
![SIMD](https://img.shields.io/badge/SIMD-a00000?style=flat-square)
![Valkey protocol](https://img.shields.io/badge/Valkey%20protocol-b22222?style=flat-square)

Кастомное in-memory хранилище, совместимое с протоколом Valkey, с поддержкой векторных операций.

<br/>

**RISC-V Дизассемблер** - `C++`

![ELF](https://img.shields.io/badge/ELF-2c003e?style=flat-square)
![RISC-V ISA](https://img.shields.io/badge/RISC--V%20ISA-4a0060?style=flat-square)
![binary](https://img.shields.io/badge/binary%20parsing-5e0080?style=flat-square)

ELF в RISC-V asm. Разбор машинного кода в читаемый ассемблер без сторонних библиотек - понимание ISA изнутри.

<br/>

**Load Balancing Benchmark** - `C++23 · Asio`

![coroutines](https://img.shields.io/badge/coroutines-004d40?style=flat-square)
![benchmarking](https://img.shields.io/badge/benchmarking-006651?style=flat-square)
![JSON](https://img.shields.io/badge/JSON%20reports-00796b?style=flat-square)
![web viz](https://img.shields.io/badge/web%20viz-00897b?style=flat-square)

Сравнение алгоритмов балансировки нагрузки на асинхронных корутинах. Настраиваемые сценарии, JSON-отчёты с детальной статистикой по латентности, отказам и распределению. Веб-интерфейс для визуализации.

<br/>

**Параметризуемый float** - `C++ · Verilog`

![IEEE 754](https://img.shields.io/badge/IEEE%20754-5d3000?style=flat-square)
![hardware](https://img.shields.io/badge/hardware-7a3f00?style=flat-square)
![e4m3fn](https://img.shields.io/badge/e4m3fn-964b00?style=flat-square)
![half / double](https://img.shields.io/badge/half%20%2F%20double-b05a00?style=flat-square)

Параметризуемый формат с плавающей точкой на C++ и Verilog: e4m3fn / e5m2 / half / double. Полный тестбенч, статистика точности.

---

### Другие проекты

| Проект | Стек | Описание |
|---|---|---|
| **Музыкальный язык + интерпретатор** | `C++` `AST` `DSP` | Собственный язык: ноты, инструменты, эффекты, функции - компилятор AST → WAV |
| **Парсер JSON** | `C++` | С подстановкой параметров и шаблонами |
| **Архиватор Хаффмана** | `C++` | Подключаемые схемы кодирования |
| **Сервис фильтрации билетов** | `C++20` `REST` `FTXUI` | Внешний API + кэш запросов + TUI |
| **Модель кэша** | `Verilog` `LRU` | LRU / bpLRU, статистика попаданий, testbench |
| **Blowfish** | `Logisim` | Аппаратная реализация алгоритма шифрования |

---

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:0a1628,70:00599C,100:0d1117&height=120&section=footer" width="100%"/>
