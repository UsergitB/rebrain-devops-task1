<h4 align="center">
  <img alt="main title" src="/common-readme/main_title.png">
</h4>

# Форматирование **Readme**
## Подзаголовок 2го уровня, форматирование текста
Немного текста с различными видами форматирования. Слово "**Bold**"  отображается жирным. Слово "_Italic_" отображается курсивом. Слово "~~Strikethrough~~" зачеркнуто. В предложении "**Сегодня _хороший_ день.**", все предложение выделено жирным, а слово "***хороший***" дополнительно выделено курсивом. А в этом предложении: "_Сегодня **хороший** день._" наоборот. Надстрочное форматирование полезно для указания степени 2<sup>10</sup>. Так же есть возможность подстрочного форматирования 2<sub>10</sub>. Этот текст: <code>Readme</code> заключен в тег code. 

## Списки
### Нумерованные списки
Ниже представлен список из 4х пунктов:
1. Первый пункт
1. Второй пункт
1. Третий пункт
1. Четвертый пункт

### Ненумерованные списки
Список:
- Пункт списка
- Пункт списка
+ Пункт списка
+ Пункт списка
* Пункт списка
* Пункт списка

При использовании разных символов, разные пропуски между строками

### Вложенные списки
Вариации вложенного списока:
1. Пункт списка
   1. Пункт списка
      - Пункт списка
        + Пункт списка
        + Пункт списка
        + Пункт списка
      - Пункт списка
   1. Пункт списка
      * Пункт списка
        * Пункт списка
        * Пункт списка
      * Пункт списка
   1. Пункт списка
1. Пункт списка

## Ссылки


**_Module consumers!_** Frustrated by each module having its own wildly unique README format? Annoyed by modules that omit critical sections like **API** or **Examples**? Stuck scrolling through API docs before you _even know what the module does_?

***Module authors!*** Tired of making up your readme format every time you write it? Do you just want consistent readmes pre-populated with your module's name, description and license without worrying about the structure every time?

What if there was a common format for the benefit of producers and consumers?

A common readme for node modules.

This can save everybody time by adhering to 4 principles:

1. **No lock in.** No special formats or tooling; run <code>common-readme</code> once for pure vanilla markdown.
1. No surprises. Pull as many details out of package.json -- like name, description, and license -- as possible. No time wasted on configuration.
1. Cognitive funnelling. Start with the most general information at the top (Name, Description, Examples) and if the reader maintains interest, narrow down to specifics (API, Installation). This makes it easy for readers to "short circuit" and continue the hunt for the right module elsewhere without wasting time delving into unnecessary details.
1. Consistency. Your brain can scan a document much faster when it can anticipate its structure.
Common format
common-readme operates on the principle of cognitive funneling.

Ideally, someone who's slightly familiar with your module should be able to refresh their memory without hitting "page down". As your reader continues through the document, they should receive a progressively greater amount of knowledge. -- perlmodstyle

Here are some READMEs generated using common-readme:

collide-2d-aabb-aabb
goertzel
twitter-kv
(Submit a pull request and add yours here!)

Usage
With npm installed, run

$ npm install -g common-readme
common-readme is a command line program. You run it when you've started a new module that has a package.json set up.

When run, a brand new README is generated and written to your terminal. You can redirect this to README.md and use it as a basis for your new module.

$ common-readme > README.md
This brand new readme will be automatically populated with values from package.json such as name, description, and license. Stub sections will be created for everything else (Usage, API, etc), ready for you to fill in.

Why?
This isn't a crazy new idea. Other ecosystems like Perl's CPAN have been benefiting from a common readme format for years. Furthermore:

The node community is powered by us people and the modules we share. It's our documentation that links us together. Our README is the first thing developers see and it should be maximally effective at communicating its purpose and function.

There is much wisdom to be found from the many developers who have written many many modules. Common readme aims to distill that experience into a common format that stands to benefit us all; especially newer developers!

Writing the same boilerplate is a waste of every author's time -- we might as well generate the common pieces and let the author focus on the content.

Scanning through modules on npm is a part of every node developer's regular development cycle. Having a consistent format lets the brain focus on content instead of structure.

The Art of README
For even more background, wisdom, and ideas, take a look at the article that inspired common-readme:

Art of README.
Install
With npm installed, run

npm install -g common-readme
You can now execute the common-readme command.

Acknowledgments
A standard readme format for the Node community isn't a new idea. Inspiration came from many conversations and unrealized efforts in the community:

standard/standard#141
richardlitt/standard-readme
zwei/standard-readme
This, in addition to my own experiences evaluating hundreds of node modules and their READMEs.

I was partly inspired by the audacity of the honey-badger-don't-care efforts of standard.

I also did a great deal of Perl archaeology -- it turns out the monks of the Perl community already did much of the hard work of figuring out great READMEs and the wisdom around small module development well over a decade ago.

Thanks to @mafintosh, @andrewosh, and @feross for many long conversations about readmes and Node.

See Also
READMEs love readme!

License
ISC
