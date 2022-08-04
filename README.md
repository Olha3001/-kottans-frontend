# Git та GitHub

I listened to the course **Introduction to Git and GitHub** for 1-2 weeks. It was a big mistake to do this after the pell-request was done. I brought for myself knowledge on -
* Git commit -a last commit when you are sure you won't change anything
* Git rm - deleting an untracked file
* Git mv - renaming a commit
* Git checkout can also cancel a command before the last snapshot
* Dash -p check not the whole file, but some changes - git reset dash -p
* Git revert - rollback - create a new commit reversed erroneous (you can git revert+ID)
* Git log (num) for example 2 - see the last 2 entries

Completed all levels [learngitbranching.js.org:]
![ScreenShot](/task_git_github/basicgit.png)
![ScreenShot](/task_git_github/remote%20repo.png)

* This course gave an understanding of the basics of git , its main commands. As well as understanding the branching of commits in git repositories
* It was interesting to go through the tutorial and see how the commands are executed.

Will I continue to use the knowledge gained in this course? - Definitely yes.

***Additional material***


### Git for 30 quills

This course provides a minimum, initial knowledge
------------------------------------------------------------------------

- [x] [Лекція по Git від Олексія Руденка](https://www.youtube.com/playlist?list=PLS8sEUxbfFY9MnPIFPTNlaS5xX7P5Ge-5)
- [x] [Git за 30 хвилин](https://codeguida.com/post/453)
- [ ]  [Git tips ](https://www.webfx.com/blog/web-design/git-tips/)
- [X] [About Merge Conflicts](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts)
- [x] [Resoilving a Merge Conflict](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line)
- [ ] [Communicating using Markdown](https://lab.github.com/githubtraining/communicating-using-markdown)
- [ ] [Learn anything front-end](https://learn-anything.xyz/web-development/front-end)
- [ ] [TypingClub ](https://www.typingclub.com/)
- [ ] [How to Learn and Cope with Negative Thoughts](https://guides.hexlet.io/learning/)

________________________________________________________________________


# Linux CLI, and HTTP


In this course, it was also interesting to go through the game to see how the teams work in action. Some of these commands I've seen before with git
![ScreenShot](/task_linux_cli/quiz1.png)
![ScreenShot](/task_linux_cli/quiz2.png)
![ScreenShot](/task_linux_cli/quiz3.png)
![ScreenShot](/task_linux_cli/quiz4.png)

Перейду на українську) 
<details><sumary>Для себе визначила кілька необхідних команд</sumary>
<ul>
<li> <em>pwd</em> щоб дізнатися шлях до поточного робочого каталогу;</li>
<li> <em>Cd</em> Для навігації за файлами та каталогами вимагається або повний шлях, або ім'я каталогу, залежно від поточного робочого каталогу, в якому ви знаходитесь. cd .. (з двома точками), щоб переміститися на один каталог вгору
<ol>
<li> cd, щоб перейти прямо в домашню папку</li>
<li> cd- (з дефісом), щоб перейти до попереднього каталогу;</li></ol></li>
<li> <em>Ls</em> Команда ls використовується для перегляду вмісту каталогу. За замовчуванням ця команда відобразить вміст вашого поточного робочого каталогу. ls -R також виведе список усіх файлів у підкаталогах
<li>
<ol>
<li> ls -a покаже приховані файли </li>
<li> ls -al виведе список файлів і каталогів з детальною інформацією, такий як дозволи, розмір, власник і т. д. якщо ви хочете переглянути вміст інших каталогів, введіть ls, а потім шлях до каталогу. Наприклад, введіть ls /home/username/Documents для перегляду вмісту в Documents.</li></ol></li>
<li> <em>cat</em> скорочення від concatenate) - одна з найбільш часто використовуваних команд в Linux. Використовується для виведення вмісту файлу командного рядка (sdout). Щоб запустити цю команду, введіть cat, а потім ім'я файлу та його розширення. Наприклад: cat file.txt. Ось інші варіанти використання команди Linux cat:
<ol>
 <li>cat filename створює новий файл</li>
<li>cat filename1 filename2>filename3 об'єднує два файли (1 і 2) і збереже їх вміст у новому файлі (3)
 Щоб перетворити файл у верхній або нижній регістр, cat filename | a-z A-Z >output.txt;</li></ol></li>
<li> <em>Cp</em> використовуйте команду cp для копіювання файлів з поточного каталогу в інший каталог. Наприклад, команда cp scenery.jpg/home/username/Pictures створить копію scenery.jpg (з вашого поточного каталогу) в каталог Pictures.</li>
<li> <em>mv</em> Основне призначення команди mv — переміщення файлів, хоча її також можна використовувати для їх перейменування.
Аргументи в mv схожі на аргументи команди cp. Вам потрібно ввести mv, ім'я файлу та каталог призначення. Наприклад: mv file.txt/home/username/Documents.</li>
Команда Linux для перейменування файлів виглядатиме так: mv starojeimia.ext novojeimia.ext.
<li> <em>mkdir</em> Використовуйте команду mkdir, щоб створити новий каталог. Якщо ви введете mkdir Music, команда створить каталог з ім'ям Music.
Додаткові команди mkdir:<ol>
<li> Щоб створити новий каталог усередині іншого каталогу, використовуйте цю базову команду Linux mkdir Music/Newfile;</li>
<li> Використовуйте опцію p (parents), щоб створити каталог між двома існуючими каталогами. Наприклад, mkdir -p Music/2020/Newfile створить новий файл «2020».</li></ol></li>
<li> <em>Rmdir</em> Якщо потрібно видалити каталог, використовуйте команду rmdir. Однак rmdir дозволяє видаляти лише порожні директорії.</li>
<li> <em>Rm</em> Команда rm використовується для видалення файлів. Якщо ви хочете видалити каталог з усім його вмістом, в якості альтернативи rmdir використовуйте rm з опцією -r.
Примітка: Будьте дуже обережні з цією командою і завжди перевіряйте, в якому каталозі ви знаходитесь. Вона видаляє все, і її неможливо скасувати.</li>
<li> <em>Touch</em> - Команда touch дозволяє створити новий порожній файл через командний рядок Linux. Як приклад введіть touch /home/username/Documents/Web.html, щоб створити файл HTML с назвою Web в каталозі Documents.</li>
<li> <em>Locate</em> Використовуйте цю команду, щоб знайти потрібний вам файл. Вона працює як команда пошуку у Windows. Більше того, аргументу -i зробить команду нечутливою до регістру, завдяки чому ви зможете шукати файли, навіть якщо ви не пам'ятаєте їх точні назви;</li>
<li> <em>find</em> Подібно до команди locate, find також виконує пошук файлів і каталогів. Різниця в тому, що команда find використовується для пошуку файлів у поточному каталозі.
Наприклад, команда find/home/-name notes.txt буде шукати файл з ім'ям notes.txt в домашньому каталозі та його підкаталогах.
Інші варіанти використання команди Linux find:<ol>
<li> Для пошуку файлів у поточному каталозі використовуйте find . -name notes.txt</li>
<li> Для пошуку каталогів використовуйте / -type d -name notes. txt4</li></ol></li>
<li> <em>Grep</em> Ще одна базова команда Linux, яка, безсумнівно, стане в нагоді для повсякденного використання grep. З її допомогою здійснюється пошук по всьому тексту у поточному файлі.
Наприклад, grep ubuntu notepad.txt буде шукати слово ubuntu у файлі notepad. Рядки, що містять слово, що шукається, будуть відображатися повністю</li>
<li> <em>Df</em> Використовуйте команду df, щоб отримати звіт про використання дискового простору в системі у відсотках та кілобайтах. Якщо ви бажаєте переглянути звіт у мегабайтах, введіть df -m.</li>
<li> <em>Head</em> Команда head використовується для перегляду перших рядків будь-якого текстового файлу. За промовчанням вона покаже перші десять рядків, але ви можете змінити це число. Наприклад, якщо ви хочете показувати лише перші п'ять рядків, введіть head -n 5 filename.ext.</li>
<li> <em>Diff</em> Будучи скороченням від англійського слова difference (різниця), команда diff порівняє вміст двох файлів рядково. Після аналізу файлів буде виведено рядки, які не збігаються. Програмісти часто використовують цю команду, коли потрібно внести зміни до програми, не переписуючи весь вихідний код.
Найпростіша форма цієї команди - diff file1.ext file2.ext.</li>
<li> <em>chmod</em> ще одна команда Linux, яка використовується для зміни дозволів на читання, запис та виконання файлів та каталогів.</li>
<li> <em>Jobs</em> Команда jobs  відображає всі поточні завдання разом з їхніми статусами. Завдання — це процес, запущений у фоновому режимі.</li>
<li> <em>kill</em> Якщо у вас є програма, що не відповідає, ви можете завершити її вручну, використовуючи команду kill. Команда відправить певний сигнал додатку, що неправильно працює, і дасть йому команду припинити роботу.</li>
<li> <em>Wget</em> Командний рядок Linux дуже корисний — ви навіть можете завантажувати файли з інтернету. Зробити це можна за допомогою команди wget. Для цього просто введіть wget і посилання для скачування.</li>
<li> <em>History</em> Регулярно користуючись Linux, ви помітите, що запускаєте сотні команд щодня. Команда history дозволяє переглянути команди, які ви вводили раніше.</li>
<li> <em>man</em> Невпевнені у функціях деяких команд Linux? Не турбуйтеся, ви можете легко навчитися використовувати їх прямо з оболонки Linux за допомогою команди man. Наприклад, man tail покаже інструкцію до команди tail.</li>
<li> <em>zip, unzip</em> Використовуйте команду zip для стиснення ваших файлів у zip-архів, а команду unzip для вилучення zip-файлів із zip-архіву</li>
<li> <em>Hostname</em> Якщо ви хочете дізнатися ім'я вашого хоста/мережі, просто введіть hostname. Додавання -I в кінці виведе IP-адресу вашої мережі.</li></ul>
                     ______________________________________________________________
                                       <h3>Бонусні поради</h3>
    Використовуйте *clear* для очищення терміналу, якщо він перевантажений попередніми командами.
Спробуйте кнопку *TAB* для автозаповнення того, що ви друкуєте. Наприклад, якщо вам потрібно набрати Documents, почніть вводити команду (наприклад, CD Docu, потім натисніть клавішу Tab), і термінал заповнить все інше, показуючи вам повну фразу CD Documents.
Комбінації клавіш *Ctrl+C і Ctrl+Z* використовуються для зупинки будь-якої команди, яка працює в даний момент. *Ctrl+C* зупиняє програму, а *Ctrl+Z* — ставить на паузу.                                   
  Якщо ви випадково заморозили термінал, натиснувши *Ctrl+S*, просто скасуйте це за допомогою комбінації *Ctrl+Q.*
*Ctrl+A* переміщає вас на початок рядка, а *Ctrl+E* — на кінець.
Ви можете запустити кілька команд в одній команді, використовуючи ";", щоб відокремити їх. Наприклад Command1; Command2; Command3. Або&&, якщо ви хочете, щоб наступна команда запускалася тільки тоді, коли попередня буде успішною. </details>

 [x] [HTTP: Протокол, який повинен розуміти кожний веб-розробник - Частина 1](https://code.tutsplus.com/uk/tutorials/http-the-protocol-every-web-developer-must-know-part-2--net-31155)

 [x] [HTTP: Протокол, який повинен розуміти кожний веб-розробник - Частина 2](https://code.tutsplus.com/uk/tutorials/http-the-protocol-every-web-developer-must-know-part-2--net-31155)


## Git Collaboration

 [x] [3 і 4 курсу Introduction to Git and GitHub](https://www.coursera.org/learn/introduction-git-github)
 [x] (Пройдіть наступні рівні learngitbranching.js.org) [https://learngitbranching.js.org/?locale=uk]

 [ ] [Flight rules for git](https://github.com/k88hudson/git-flight-rules/blob/master/README_ru.md) цей курс потрохи роздруковуєсться та вішається на стіну перед очима, там зібрано майже все що має статися в нагоді на протязі усієї роботи не тільки в новачків.

[x] [Oh shit, git!](https://ohshitgit.com/ru) Дуже доступною мову і зрозуміло написано))) Забрала собі в скарбничку
[x] [GitHub Skills](https://github.com/skills/resolve-merge-conflicts) Це також забрала собі на в читання перед сном)
![ScreenShot](/task_git_collaboration/basicgit.png)
![ScreenShot](/task_git_collaboration/remote%20repo.png)
