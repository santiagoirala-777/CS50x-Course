# Week 0 — Scratch & Computational Thinking

## 📍 Progress Tracker

- **Última sesión registrada:** `08/10/2026` (21:24 – 22:00)
- **Punto exacto donde retomar el video:** [**Minuto `29:54` (`start=1794`) — Inicio de ASCII ("Here is the letter A...")**](https://video.cs50.io/UuIEbpQms8o?start=1794)
- **Recursos oficiales de Week 0:** [Página de Week 0](https://cs50.harvard.edu/x/2026/weeks/0/) · [Lecture Notes](https://cs50.harvard.edu/x/2026/notes/0/) · [Problem Set 0](https://cs50.harvard.edu/x/2026/psets/0/)

---

## ⚡ Inbox de Captura Rápida (Tus Keywords en Vivo)

> **Cómo usar esta sección:** Mientras mirás la clase, **no pierdas tiempo armando tablas ni redactando definiciones**. Escribí acá abajo solo palabras clave sueltas, frases rápidas o el minuto aproximado (ej. `- ASCII = 65 es la A`, `- Unicode emojis`, `- pseudocode`). Cuando termines tus 20–30 minutos, decime *"Tyler, formateame los apuntes de hoy"* y yo convierto todo en filas prolijas dentro de la tabla de abajo con su definición exacta y su link directo al minuto del video.

- *(Escribí acá tus próximas palabras clave a partir del minuto `29:54`...)*
- 

---

## 📚 Table of Contents & Conceptos Consolidados (`00:00` → `29:54`)

| Content / Term | Meaning & Core Explanation | Video Timestamp |
| :--- | :--- | :---: |
| **AI & CS Fundamentals** *(Intro)* | AI removes human bottlenecks, but mastering computer science fundamentals keeps you in the driver's seat ("the pilot"). | [02:25](https://video.cs50.io/UuIEbpQms8o?start=145) |
| **VS Code, API & `chat.py`** *(Intro)* | Quick demo of a code editor & terminal: connecting to OpenAI's **API** (*Application Programming Interface*) using `user_prompt` and `system_prompt` in ~10 lines of Python. | [04:48](https://video.cs50.io/UuIEbpQms8o?start=288) / [06:23](https://video.cs50.io/UuIEbpQms8o?start=383) |
| **Rubber Duck Debugging (`cs50.ai`)** | Explaining your code out loud to a rubber duck to catch logic bugs. In CS50x, using `cs50.ai` (Virtual Duck) is encouraged; external AIs (ChatGPT/Gemini/Claude) are not allowed for solving problem sets. | [12:30](https://video.cs50.io/UuIEbpQms8o?start=750) |
| **Computer Science** | **The study of information** — how to represent it and how to process it — applied to problem-solving. | [14:27](https://video.cs50.io/UuIEbpQms8o?start=867) |
| **Computational Thinking** | Applying ideas from computer science to solve real-world problems methodically. | [14:31](https://video.cs50.io/UuIEbpQms8o?start=871) |
| **Problem Solving (`Input → Output`)** | Taking an **input** (the problem to solve), processing it through an **algorithm** ("black box"), and producing an **output** (the solution). | [14:59](https://video.cs50.io/UuIEbpQms8o?start=899) |
| **Unary Notation (`Base-1`)** | Counting system with a single symbol (like counting on human fingers where each finger just adds $+1$; 5 fingers = max `5`). | [15:39](https://video.cs50.io/UuIEbpQms8o?start=939) |
| **Binary System (`Base-2`)** | Positional counting system that uses only **2 symbols (`0` and `1`)**, matching physical electricity (`OFF` / `ON`). With 5 fingers in binary you can count from `0` up to `31` ($32$ combinations). | [16:09](https://video.cs50.io/UuIEbpQms8o?start=969) / [17:27](https://video.cs50.io/UuIEbpQms8o?start=1047) |
| **Bit (`Binary Digit`)** | Portmanteau of **bi**nary digi**t**: the smallest unit of information in a computer (`0` or `1`). | [17:49](https://video.cs50.io/UuIEbpQms8o?start=1069) |
| **Transistors** | Computers don't have literal light bulbs inside, but they have **millions/billions of microscopic switches called transistors** that turn `ON` (`1`, holding charge) or `OFF` (`0`, no charge). | [19:27](https://video.cs50.io/UuIEbpQms8o?start=1167) |
| **Decimal System (`Base-10`)** | Human positional system with **10 digits (`0` → `9`)**. Each column is a power of 10: $10^2 (100),\, 10^1 (10),\, 10^0 (1)$ (e.g., $123 = 100\times 1 + 10\times 2 + 1\times 3$). | [21:32](https://video.cs50.io/UuIEbpQms8o?start=1292) / [23:00](https://video.cs50.io/UuIEbpQms8o?start=1380) |
| **Binary Positional Powers ($2^n$)** | Because binary only has 2 symbols (`0` and `1`), each column is a **power of 2**: $\dots, 2^2 (4),\, 2^1 (2),\, 2^0 (1)$. With 3 bits: `000` ($0$) to `111` ($4+2+1 = 7$). Trying to represent `8` with only 3 bits causes an **overflow** back to `000`. | [23:42](https://video.cs50.io/UuIEbpQms8o?start=1422) / [25:26](https://video.cs50.io/UuIEbpQms8o?start=1526) |
| **Byte (`8 Bits`)** | A single bit is too small to be useful alone, so computers group **8 bits = 1 Byte** (columns: $128, 64, 32, 16, 8, 4, 2, 1$, i.e., $2^7 \dots 2^0$). | [26:26](https://video.cs50.io/UuIEbpQms8o?start=1586) |
| **8 Bits = $2^8 = 256$ Values** | With 1 byte (`8 bits`), there are **$2^8 = 256$ possible combinations**: from `00000000` ($0$) up to `11111111` ($255$). Modern hardware also groups 32 bits ($\approx 4\text{ billion}$) or 64 bits. | [27:11](https://video.cs50.io/UuIEbpQms8o?start=1631) / [27:42](https://video.cs50.io/UuIEbpQms8o?start=1662) |

---

## 🗺️ Lo que viene desde el minuto `29:54` (Mapa de ruta del resto de Lecture 0)

1. **Text (`ASCII` & `Unicode`)** — [29:54](https://video.cs50.io/UuIEbpQms8o?start=1794): Cómo se representan letras (`A = 65`), acentos y emojis con bits y bytes.
2. **Colors (`RGB`), Images, Video & Audio** — Cómo 3 bytes (`Red, Green, Blue`) forman cada píxel, cómo las imágenes en secuencia forman video y cómo se representan notas musicales.
3. **Algorithms & Running Time (`Big-O`)** — El ejemplo de la guía telefónica (*Phone Book*): búsqueda lineal vs. búsqueda binaria (dividir a la mitad, $\log_2 n$).
4. **Pseudocode** — Funciones, condicionales (`if / else if / else`), expresiones booleanas y bucles (`loops`).
5. **Scratch** — Bloques visuales en MIT Scratch (`say`, `ask`, `forever`, `if`, eventos, sprites y creación de tu propio bloque/función).

---

<details>
<summary>🗄️ Respaldo literal de tus apuntes originales del 08/10/2026 (Recuperados del snapshot <code>zT3r.md</code> de VS Code)</summary>

```markdown
# Week 0 — Scratch

08/10/2026
Today i've watched the video up to the minute : "https://video.cs50.io/UuIEbpQms8o?start=1794"

## Table of contents

| Content          |       Meaning        |                                        Time |
| :--------------- | :------------------: | ------------------------------------------: |
| Computer Science | Study of information | https://video.cs50.io/UuIEbpQms8o?start=867 |

### Lista a agregar (Tyler debes formatear todo mejor entendiendo que quiero hacer.)

- Computational thinking 14.35
- Unary notation and binary = Base-1 and base-2 systems
- Binary digit ---<> BIT
- Computers dosn't have little bulbs inside, but they have millions of tiny little things called transitors
- Base-10 System = Decimal system (Ten digits: 0 -->9) 10 to 1, 10 to 2, etc
- Binary = 2 to 0, 2 to 1, 2 to 2, etc (Because we only have 2 symbols)
- 8 BITS = 1 Byte
- 8 bites = 256 (2 to 8)
-

Tyler si lees esto, necesito ayuda para ver como ir haciendo este documenbto, y que debop agregar a medida que avanzo con el video de la week 0, que agregar, como hacerlo, con que formato, y que no y decime y explicame todo.
Capaz conviene crear un solo archivo.md para la table of contents aparte. Yo voy a ir anotantdo palabras claves para no perder la velocidad con el curso ya que es largo, pero luego tu deberás completar las definiciones, y todo.
```

</details>
