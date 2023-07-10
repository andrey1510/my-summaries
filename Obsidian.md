#obsidian


[Obsidian + Dataview: Таблицы / Хабр (habr.com)](https://habr.com/ru/post/710356/)

[Часть 1. Управление знаниями в Obsidian. Обработка информации. Рабочий процесс. Источники информации. Работа с заметками / Хабр (habr.com)](https://habr.com/ru/post/710508/)

[Воспитание Obsidian — вашего персонального информационного менеджера / Хабр (habr.com)](https://habr.com/ru/company/macloud/blog/560776/)

[Импортозамещаем Evernote. Obsidian – менеджер заметок и лучший друг менеджеров / Хабр (habr.com)](https://habr.com/ru/company/ru_mts/blog/705572/)

### Formats

**Bold**
==Highlight==
*Italics*
`Code`
~~Strikethrough~~
Comment(hidden)%%Comment%%

Внутренняя ссылка:
[[Obsidian]]
Встраивание документа: ![[]]
Внешняя ссылка:
[hyperlink](https://github.com/malykhin-sergei/obsidian-howto)


Горизонтальная черта
---


### Admonition plugin

```ad-hint
collapse: open
title: Admonition plugin usage 
color: 10, 200, 4



Code view sample 
~~~~~ java

public class Rezyser {

@Id
@GeneratedValue
private Long id;
private String imie;
private String nazwisko;
private Date data_urodzenia;
private String kraj_pochodzenia;

@OnDelete(action = OnDeleteAction.CASCADE)
@OneToMany(mappedBy = "rezyser")
private List<Film> filmList;

public Rezyser(String imie, String nazwisko, Date data_urodzenia, String 
kraj_pochodzenia) {
    this.imie = imie;
    this.nazwisko = nazwisko;
    this.data_urodzenia = data_urodzenia;
    this.kraj_pochodzenia = kraj_pochodzenia;
}
//getters, setters, toString and creators

~~~~~

```



### Excalidraw plugin 

![[Drawing 2023-03-01 19.12.19.excalidraw]]


~~~~

class Money { // ... public Money(double amount, Currency currency) { this.amount = amount; this.currency = currency; } public Currency getCurrency() { return currency; } public double getAmount() { return amount; } }

~~~~
