<!--
language: de
narrator: Deutsch Female
-->

- GitHub: https://github.com/MINT-the-GAP/Demo-2025
- LiaScript: https://liascript.github.io/course/?https://raw.githubusercontent.com/MINT-the-GAP/Demo-2025/refs/heads/main/README.md
- LiveEditor: https://liascript.github.io/LiveEditor/?/show/file/https://raw.githubusercontent.com/MINT-the-GAP/Demo-2025/refs/heads/main/README.md


# LiaScript Demo / Tutorial

    --{{0}}--
Die Idee für LiaScript entstand 2017 im "Industrial eLab-Projekt".
Darin ging es um die Entwicklung von Online-Laboren für die Lehre in den Ingenieurwissenschaften.
Wir suchten nach einer Möglichkeit, schnell und einfach Lehrinhalte im Team zu produzieren.
Markdown als eine einfach zu erlernende und bereits etablierte Markup-Sprache (Englisch für "Auszeichnungssprache") bot sich hier als gemeinsame Grundlage an.

    --{{1}}--
Markdown ist mittlerweile ein Standard für Blogging (JAM-Stack) oder die Dokumentation von IT-Projekten (GitHub), mit Editoren in Moodle und Co. Sie nutzen vielleicht sogar schon Markdown, ohne es zu wissen. Versuchen Sie mal die folgende Nachricht über WhatsApp zu verschicken und schauen, was passiert:


      {{1}}
`Teig`\
_Tomaten_ und _Käse_\
~keine Salami~

    --{{1}}--
Mithilfe solcher Annotationen ermöglicht Markdown einfache Formatierungen wie
`Code`,
_Kursiv_,
__Fett__ und
~Durchgestrichenes~
in Texten zu verwenden.
Diese können auch miteinander kombiniert/verschachtelt werden.

      --{{2 Russian Female}}--
Первоначально создан в 2004 году Джоном Грубером (англ. John Gruber) и Аароном
Шварцем. Многие идеи языка были позаимствованы из существующих соглашений по
разметке текста в электронных письмах...


## Struktur

Texte lassen sich ähnlich einfach strukturieren:

Ein Absatz kommt selten allein ...

- Eine Aufzählung
- Mit verschiedenen
- Unter-Punkten

| Tabellen |  sind   | leichter |
| -------- | :-----: | -------: |
| als      | gedacht |      und |
| selbst-  |   er-   |  klärend |

## Multimedia

[LiaScript Webseite](https://liascript.github.io)

---

[Bild: Turmbau zu Babel](https://raw.githubusercontent.com/LiaPlayground/Warum-offene-Bildung-eine-Sprache-braucht/refs/heads/main/img/babel.jpg)

---

[audio](https://soundcloud.com/mozart/sets/mozart-piano-sonatas)

---

[YouTube](https://www.youtube.com/watch?v=U_UW69w0uHE)

---

[embed](https://sketchfab.com/3d-models/esthers-scroll-in-a-cover-21a13eba33cb4343bab56f0c0f982876)

---

[embed](https://phet.colorado.edu/sims/html/gases-intro/latest/gases-intro_all.html)

### ASCII-Art

                                    Multiline
    1.9 |    DOTS
        |                 ***
      y |               *     *
      - | r r r r r r r*r r r r*r r r r r r r
      a |             *         *
      x |            *           *
      i | B B B B B * B B B B B B * B B B B B
      s |         *                 *
        | *  * *                       * *  *
     -1 +------------------------------------
        0              x-axis               1

## Quizzes

What did the **fish** say when he hit a **concrete wall**?

    [[dam]]

Multiple Choice
---------------

Just add as many points as you wish:

    [[X]] Only the **X** marks the correct point.
    [[ ]] Empty ones are wrong.
    [[X]] ...

Single Choice
-------------

Just add as many points as you wish:

    [( )] ...
    [(X)] <-- Only the **X** is allowed.
    [( )] ...

### Mehr Quizze

                    {{UK English Female |>}}
The film that I saw [[(that)|those|these|then]] night wasn’t very good.
It was all [[ about ]] a man [[ who ]] built a
time machine so he [[ could ]] travel back in time.
It took him ages and ages [[ to ]] build the machine.

Noch mehr in der [Dokumentation](https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#73)


### Tabellen

| Animal          | weight in kg | Lifespan years | Mitogen |
| --------------- | ------------:| --------------:| -------:|
| Mouse           |        0.028 |              2 |      95 |
| Flying squirrel |        0.085 |             15 |      50 |
| Brown bat       |        0.020 |             30 |      10 |
| Sheep           |           90 |             12 |      95 |
| Human           |           68 |             70 |      10 |

---

| Classic | Country | Reggae | Hip-Hop | Hard-Rock | Samba |
| -------:| -------:| ------:| -------:| ---------:| -----:|
|      50 |      50 |    100 |     200 |       350 |   250 |

## Ausführbarer Code

```javascript
var s = "JavaScript syntax highlighting";
console.log(s);
```

## Mehr

- https://github.com/liascript/CodeRunner
- https://github.com/topics/liascript-template