# Awesome resources for LMC developers [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of amazingly awesome resources for (not only) LMC developers.

The aim is to provide a list of "must-read" resources about not widely known or often neglected topics.
If you get through them, they will surely make you a better and even more awesome developer - we promise!

- 🇨🇿 Resource is in Czech (otherwise it is in English)
- 🎥 Resource is a video (otherwise it is an article)

## Table of Contents
- [Development](#development)
- [Code review](#code-review)
- [Q&A](#qa)
- [Git](#git)
- [Books](#books)
- [Newsletters](#newsletters)

### Development
- [Fluent interfaces are evil](https://ocramius.github.io/blog/fluent-interfaces-are-evil/) - there are actually very few cases when fluent interfaces should be used.
- Article series by Matthias Noback:
    - [Reducing complexity](https://www.ibuildings.nl/blog/2016/01/programming-guidelines-part-1-reducing-complexity)
    - [Getting rid of null](https://www.ibuildings.nl/blog/2016/01/programming-guidelines-part-2-getting-rid-null)
    - [Why write tests](https://www.ibuildings.nl/blog/2016/08/why-write-tests)
- [Principy objektově orientovaného návrhu](https://www.zdrojak.cz/serialy/principy-objektove-orientovaneho-navrhu/) (🇨🇿) - article series covering SOLID and GRASP patterns.
- [Verzování Databáze](https://www.youtube.com/watch?v=KTmlw5AKM8E) (🇨🇿 🎥) - why and how to migrate your database with backward-compatibility.
- [Technický dluh](https://blog.think-forth.com/2016/01/21/technicky-dluh/) (🇨🇿)
- [Compare JSON: Object Keys, Array Order and Record IDs](https://bestjson.com/learn/compare-json-ignore-order) - Explains how array order, duplicate counts and record IDs affect JSON comparison results.

#### PHP-specific
- [Extremely Defensive PHP](https://ocramius.github.io/extremely-defensive-php/#/) - Avoid mistakes. Be cautious about your code.
- [Named constructors](http://verraes.net/2014/06/named-constructors-in-php/) - especially value objects may be better instantiated via static named constructors, instead of `__construct()`.
- [Symfony komponenty](https://www.zdrojak.cz/serialy/symfony-po-kruckach/) (🇨🇿) - article series about standalone Symfony components.
- [Dealing with exceptional conditions](https://www.youtube.com/watch?v=1YAGxJVuuws) (🎥) - best practices for dealing with exceptions in PHP.
    - Main ideas are also summed [in an article](https://blog.nikolaposa.in.rs/2016/08/17/exceptional-behavior-best-practices/).

### Code review
- [Code reviews v praxi](https://www.zdrojak.cz/clanky/code-reviews-praxi/) (🇨🇿)
- [Code review checklist](https://www.zdrojak.cz/clanky/code-review-checklist/) (🇨🇿)
- [Co nás naučilo code review](https://www.zdrojak.cz/clanky/co-nas-naucilo-code-review/) (🇨🇿)

### Q&A
- [Funkční systémové testování: když unit-testy nestačí](http://prvnivcesku.cz/systemove-testovani/) (🇨🇿) - what is functional system testing and when to use it.

### Git
- [Jak a proč fixupovat](https://filip-prochazka.com/blog/git-fixup) (🇨🇿) - how and why use fixup commits (especially during code-reviews).

### Books
- [Clean code - Rober C. Martin](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
- [Návrhové vzory - Rudolf Pecinovský](http://knihy.pecinovsky.cz/vzory/index.html) (🇨🇿)

### Newsletters
- [PHP Annotated monthly by Jetbrains](https://blog.jetbrains.com/phpstorm/category/php-annotated-monthly/)
- [PHP Weekly](http://www.phpweekly.com/)

## Contributing rules
If you feel some resource matching aim of this document (see the beginning) is missing, you are welcome to contribute!
But please follow this rules:

- Add one new resource per one pull request.
- Use icons (🇨🇿 🎥 ...) if applicable.
- Add short description why the resource is awesome. The description sentence should end by a dot.
- If the resource is in Czech, make the title (link) also in Czech, but the description should be always in English.
- Also please note this list is *curated*, as we want it to contain only the most important resources. This means
suggestions are not automatically accepted and may be rejected if we feel they does not match the mission of this document.
