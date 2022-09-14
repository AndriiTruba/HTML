# **PERSONAL ASSISTANT**
###### goit python group project - group № 10 
###### group name - "3TSoft"

------------
##  Опис та інструкція по роботі з Асистентом

**«Асистент»** - це ваш персональний помічник із книгою контактів, нотатками та папками. При запуску асистента користувачу показується меню з яким він далі працює.

**«Асистент» вміє:**
- зберігати, видаляти та змінювати контакти у вашій книзі контактів
- Перевіряти дні народження ваших контактів у заданому періоді часу
- створювати, видаляти та змінювати ваші нотатки
- впорядковувати файли на вашому ПК по категоріям
------------

#### Встановлення

Для встановлення даного персонального помічника вам потрібні ***python 3.6+*** та ***pip***.

- Скопіюйте репозиторій на ваш комп'ютер
- Перейдіть до директорії project_3TSoft
- Запустіть командний рядок (cmd)
- Пропишіть команду: **`pip install -e .`**

Для запуску, вам потрібно прописати команду **`project_3TSoft`** в cmd, від імені адміністратора 

------------

###  «Асистент» працює з наступними командами:

| Назва команди |  Дія |
| ------------ | ------------ |
|||
|**Головне меню:**||
| `> 1) Menu adress book` | відкрити меню контактів |
| `> 2) Menu notes`  | відкрити меню нотатків |
| `> 3) Menu sorted`  | відкрити меню сортування папок |
| `>>> 0: Exit to main menu`  | відкрити меню сортування папок |
|||
|**1) Меню взаємодії з контактами:**||
| **`> 1) Add new contact`** | Меню додавання контакта: |
|||
| `- 1) Phones`  | додати номер телефону |
| `- 2) Email`  | додати електронну почту |
| `- 3) Adress`  | додати адресу |
| `- 4) Birthday date`  | додати дату дня народження |
| `- 5) Notes`  | додати нотатку |
| `- 0: Exit to main menu`  | вихід до попереднього меню |
|||
| **`> 2) Change contact`** | Меню редагування контакта: |
|||
| `- 1) Phones`  | редагувати номери телефону |
| `- 2) Email`  | редагувати електронну почту |
| `- 3) Adress`  | редагувати адресу |
| `- 4) Birthday date`  | редагувати дату дня народження |
| `- 5) Notes`  | редагувати нотатку |
| `- 0: To enter the contact menu.`  | вихід до меню контактів|
|||
| **`> 3) Delete contact`** | Меню видалення контакта: |
|||
| `- 1) Some fields in contact`  | видалити деякі поля контакту |
| `- 2) Contact`  | видалити контакт |
| `- 0: To enter the contact menu.`  | вихід до меню контактів|
|||
| **`> 4) Find similar`** | знайти контакт по символах|
|||
| **`> 5) Show contact`** | показати декілька контактів  |
|||
| **`> 6) Show all contacts`** | показати всі контакти|
|||
| **`> 7) Show contact's birthday dates`** | показати дні народження за певний період|
| **`>>> 0: To exit in main menu.`** | повернутися у головне меню|
|||
|**2) Робота з нотатками**||

------------

<p align="center">
<img src="https://github.com/AndriiTruba/-pictures/blob/main/menu_notes.png">
</p>

------------

| **`Write text to find`** | Введіть текст для пошуку нотаток: |
| `- By article`  | пошук по назві |
| `- By tags`  | пошук по тегам(ключовим словам) |
| `- By text`  | пошук по тексту нотатки  |
| **`Show all articles`** | виводить список всіх нотатків |
|||
| **`Sort by`** | Введіть текст для пошуку: |
| `- Alphabet` | додавання нової нотатки |
| `- Date change` | показати нотатки |
|||
| **`Write text to`** | Введіть заголовок нотатки для: |
| `- Read`  | відкриття нотатки для читання |
| `- Change`  | відкриття нотатки для редагування |
| `- Delete`  | видалення нотатки |
|||
| **`> 1) Add new article`** | додати нову замітку: |
|||
</p>
<img src="https://github.com/AndriiTruba/-pictures/blob/main/menu_add_note.png">
</p>

------------

|**Меню сортування файлів**||
|||
| `- 1) >>> Chose folder to work whit it! <<<`  |  введіть повний шлях до папки |
| `- 2) Start clean folder`  | відсортувати папку |
| `- 3) Open folder after clean`  | відкрити відсортовану папку |
| `- 4) Open read file after clean`  | відкрити файл з описом сортування |
| `- 0: Exit to main menu`  | вихід до попереднього меню |
| ------------ | ------------ |

------------
‎
## Description and instructions in English

**«Fellow»** is your personal friend and assistant with a contact book, notes, and some additional features.

**«Fellow» can**
- save, delete and edit contacts in your contact book
- сheck the birthdays of your contacts in the specified time period
- save, delete and modify your notes
- sort files on your PC by categories
------------

#### Installing

To install this personal assistant, you need ***python 3.6+*** and ***pip***.

- Copy the repository to your computer
- Go to the fellow directory
- Run the command prompt (cmd)
- Write the command: **`pip install -e .`**

To run, you should write a command **` fellow`** in the cmd as an administrator.

------------

###  "Fellow" works with the following commands:

| Command name |  Acting |
| ------------ | ------------ |
|||
|**Work with contacts**||
| `add contact` | add a new contact |
| `show contacts`  | show contacts |
| `find contact "сontact name"`  | find contact phone number |
| `delete contact "сontact name"` | delete contact |
| `get birthdays` | show birthdays |
| `back` | back to main menu|
|||
|**Work with notes**||
| `add note` | add a new note |
| `show notes` | show notes |
| `change note` | change the note |
| `delete note "note title"` | delete a note |
|||
|**Sort files**||
| `sort folder` | sort files in the specified folder |

