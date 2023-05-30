# Туториал по основам системы контроля версий GIT 


## Инициализация проекта 
**Чтобы добавить возможность использовать разные версии файлов, необходимо использовать следующую комманду:**

``` fix
git init
```

## Как добавить файл в отслеживание
**Чтобы добавить файл на отслеживание, используйте следующую коммманду:**

```fix
git add . 
```

## Как вывести на экран истории всех коммитов 
**Чтобы вывести на экран истории всех коммитов с их хеш-кодами надо написать:**

```fix
git log
```

## Как перейти от одного коммита к другому
**Чтобы это сделать, используйте следующую комманду**

```fix
git chekout
```

## Как вернуться к актуальному состоянию и продолжить работу
**Чтобы сделать это, надо прописать следующую комманду**

```fix
git checkout main
```

# Краткое руководство по MarkDawn


## Заголовки 




## Исходный код

**В чистом Маркдауне блоки кода отбиваются 4 пробелами в начале каждой строки. Но в GitHub-Flavored Markdown (сокращенно GFM) есть более удобный способ: ставим по три апострофа (на букве Ё) до и после кода. Также можно указать язык исходного кода.**

```html
<nav class="nav nav-primary">
  <ul>
    <li class="tab-conversation active">
      <a href="#" data-role="post-count"
class="publisher-nav-color" data-nav="conversation">
        <span class="comment-count">0
комментариев</span>
        <span class="comment-count-placeholder">комментарии</span>
     </a>
 </li>
 <li class="dropdown user-menu" data-role="logout">
    <a href="#" class="dropdown-toggle" data-toggle="dropdown"
       <span class="dropdown-toggle-wrapper">
          <span>
            Войти
          </span>
        </span>
        <span class="caret"></span>
       </a>
     </li>
   </ul>
</nav>
```

**Самое приятное, что в коде не нужно заменять угловые скобки `< >` и амперсанд `&` на их html-сущности.**


## Таблицы 

**В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.**

First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell

**Для красоты можно и по бокам линии нарисовать:**

| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

**Можно управлять выравниванием столбцов при помощи
двоеточия.**

| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |

**Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.
Для всего остального есть обычный HTML**

## Изображения

**Чтобы добавить изображения, воспользуйтесь следующей коммандой:** 

```
![Альтернативный текст](ссылка на это фото)
```
Например: 


![Спорт](https://plus.unsplash.com/premium_photo-1684923610356-001513e75d62?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=987&q=80)

**Если вы хотите добавить имеющиеся фото , то:** 


![Здесь был Ваня и его фото](Vania.jpg)

**Если мы хотим добавить изображения-ссылки, то нашу конструкцию нужно сделать такой:**

```
![[альтернативный текст(ссылка)]](Ссылка на другую картинку - наш перевертыш)
```

[![Фото Васи и Пети - нажми, получишь бонус](https://img3.labirint.ru/rc/abb693298c841ee6d231ca671f7b5d17/363x561q80/books15/147125/cover.jpg?1280394613)](https://plus.unsplash.com/premium_photo-1684923610356-001513e75d62?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=987&q=80)

