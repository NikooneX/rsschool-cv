# **_Nikolai Khmelnitskiy_**

**Junior Frontend Developer**
![Foto](/rsschool-cv/assets/img/Me150.jpg)
Engineer mechanic and control systems

---

**Born:** 01.06.1985<br>
**Site:** Lithuania, Vilnius<br>
**Language:** Native Russian. English A2→B1<br>
**Education:** Higher technical education - mechanical engineer<br>
**Telephone:** +370 676 156 29 (Lithuania) Telegram, Whatsapp, Viber<br>
**Email:** niko.xme@gmail.com<br>
**[Linkedin](https://www.linkedin.com/in/nikolai-khmelnitski-7a567a235/)**<br>
**[GitHub](https://github.com/NikooneX)**<br>

---

# **ABOUT MYSELF**

I have worked as an engineer for the last 17 years. During this time, I went from an ordinary mechanical engineer to a co-founder of my own company. Thanks to the craving for knowledge, I thoroughly understood how complex gas and diesel generator sets work. I learned how to repair them, diagnostics them, and later performed installation supervision and commissioning of new equipment [Caterpillar](https://www.youtube.com/watch?v=pwzOxDD730c)

For the last 4 years I have been working in my own company. We manufactured, installed and commissioned [control systems](https://www.youtube.com/watch?v=iGLluRhZfn4) for gas and diesel generator sets. As I worked, I increasingly wanted to learn how computer programs are created and run the "iron" (hardware)

I am currently studying IT. While studying Python, I liked to solve varying complexity problems with the help of logic and knowledge of syntax. Now studying the front-end, I like to see the result of my work

I know that my ability to learn and technical mind will help me become a professional developer.

---

# **WORK EXPERIENCE**

## Co-founder _LLC Energofix_

Activities _(Dec/2018 - Till now / Minsk, Belarus)_

- Manufacturing, upgrade, installation, commissioning of control cabinets for diesel and gas generator sets (CAT, MWM, Perkins...)
- Repair, maintenance, commissioning, diagnostics gen sets

Achievements

- Manufacture, installation and commissioning of the control cabinets for 2 diesel gen sets CAT C18 (island mode), CAT 3516B (island mode TIER III). Performs the functions of automatic start / stop of gen sets, load sharing, protection, SCADA
- Retrofit the control system of 3 CAT G3520C gas gen sets and 2 MWM CG132V12 with the replacement of controllers

## Leading mechanical engineer, head of gas engines service department _LLC Zeppelin Belarus_

Activities _(Mar/2012 – Dec/2018 / Minsk, Belarus)_

- Organization of work of mechanical engineers. Work with clients. Work with the CAT support service. Participation in technical seminars for dealers. Investigation of difficult cases of breakdowns/diagnostics of gen sets. Conducting trainings for clients. Installation, supervision, commissioning, repair, maintenance, diagnostics of diesel and gas gen sets (Caterpillar G3500 C&E, 3500; MWM CG170/132; Perkins) with various control systems (TemEvo, Terberg, ComAp, Woodward, EMCP, Datakom, Deif...), various operating modes (parallel, island, emergency)

## Mechanical engineer _LLC New Technologies_

Activities _(Jan-2011 - Mar-2012 / Minsk, Belarus)_

- Repair, maintenance, diagnostics Horizontal Directional Drilling the Vermeer and equipment. Purchase of spare parts. Documents<br>

## Equipment repair master _Republican Unitary Enterprise Minsk Tractor Works_

Activities _(Apr-2005 - Jan-2011 / Minsk, Belarus)_

- Organization of the work of locksmiths repairmen of the heat treatment shop. Ordering spare parts, working with drawings, doc. Many rationalization proposals for improving equipment

---

# **SKILLS & PROFICIENCY**

|     HTML     |   CSS   |     JS      |
| :----------: | :-----: | :---------: |
|  **Python**  |         | **GitHub**  |
| **Markdown** | **Git** | **VS Code** |

---

# **CODE EXAMPLE**

1. На вход программе подается натуральное число nn, затем nn строк, затем число kk — количество поисковых запросов, затем kk строк — поисковые запросы. Напишите программу, которая выводит все введенные строки, в которых встречаются все поисковые запросы

```
d = int(input())
s1 = []
for i in range(d):
    s1.append(input())
k = int(input())
s2 = []
s3 =[]
for j in range(k):
    s2.append(input())
for i in s1:
    count = 0
    for j in s2:
        if j.lower() in i.lower():
            count += 1
    if count == len(s2):
        s3.append(i)
print(*s3, sep='\n')
```

2. На вход программе подается натуральное число nn, а затем nn различных натуральных чисел, каждое на отдельной строке. Напишите программу, которая выводит наибольшее и второе наибольшее число последовательности

```
n = int(input())
large = -1
prelarge = -2
for i in range(n):
    num = int(input())
    if num > large:
        prelarge = large
        large = num
    elif num < large and num > prelarge:
        prelarge = num
print(large)
print(prelarge)
```

3. My first CSS)))

```
body {
    max-width: 70%;
    margin: auto;
}
h1, h2, h3 {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin-top: 1.5em;
}
h1 {
    font-size: 32px;
}
table, th, td {
    border: 1px solid black;
}
figcaption {
    font-style: italic;
}
figure {
    float: right;
    clear: right;
}
```

---

# **EDUCATION AND CERTIFICATES**

_Name:_ RS School (2022, in progress)<br>
_Training:_ Курс «JavaScript/Front-end»

_Name:_ Школа BEEGEEK (2022)<br>
_Training:_ Вебразработка для начинающих HTML/CSS

_Name:_ EPAM Learn Digital Platform (2022)<br>
_Training:_ IT Fundamentals

_Name:_ Школа BEEGEEK (2022)<br>
_Training:_ "Поколение Python": курс для начинающих

_Name:_ ComAp training center, Czech Republic (2019)<br>
_Training:_ Advanced Plus (engines control system)

_Name:_ Marelli Generator training center, Italy (2017)<br>
_Training:_ Marelli Generator Functions, Analog and Digital AVR Setting and Troubleshooting

_Name:_ Terberg training center, Netherlands (2017)<br>
_Training:_ Industrial Control System for Gas engines

_Name:_ ZEPPELIN Rusland (2015)<br>
_Training:_ Expert category C (Caterpillar)

_Name:_ Caterpillar Energy Solutions, Germany (2014)<br>
_Training:_ Total Electronic Management – TEM EVO and Gas Engines – Basics and Periphery Components

_Name:_ Caterpillar, Moscow (2013)<br>
_Training:_ Warranty Training

_Name:_ Caterpillar Malaga Demonstration and Learning Center (2013)<br>
_Training:_ G3500 C&E Electronic Engine / MDLC G3500 Lean Burn Engines

_Name:_ Belarusian National Technical University (Belarus, Minsk), Automotive Faculty (2003 – 2009)<br>
_Specialty:_ Engineer-Mechanical

_Name:_ Zhodino professional lyceum (Belarus 2000-2003)<br>
_Specialty:_ Car mechanic, category B and C driver

---

# **COMPETENCIES**

Goal oriented | Problem-solving

| Thinking through first principles |

Troubleshooting | Results-driven

Resilience | Leadership | Reliable

Avid learner | Teamwork
