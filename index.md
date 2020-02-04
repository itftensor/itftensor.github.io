---
layout: page
title: 21 февраля 2020
excerpt:
comments: true
---
Привет!

Мы Тензор –федеральный IT-холдинг (подробнее о нашем продукте здесь: [**СБИС**][sbis]).
Мы организуем встречи, конференции и другие классные мероприятия для IT-сообществ в разных городах от Калининграда до Новосибирска:

[**Калининград**][kltf]

[**Тюмень**][tmnconf] 

[**Новосибирск**][1070873]

[**Кострома**][1040266] 

[**Ярославль**][1050019] [**yarfrontend.ru**][yarfrontend]
и др.

Начать 2020 год мы решили со знакомства с ивановскими программистами. 

Если  ты  опытный  разработчик,  хочешь  весело  и  с  пользой  провести  время  в  компании  единомышленников, приглашаем тебя на наш праздничный Meetup в честь Дня защитника отечества. Регистрируйся и приходи.

<a class="register-link__button" href="https://kompaniya-tenzor-events.timepad.ru/event/1247224/">Регистрация</a>

Что тебя ждет:

• Четыре интереснейших доклада от доблестных программистов Тензора;

• Крутые конкурсы и лотерея с подарками для настоящих мужчин;

• Армейский кофе-брейк и бомбическое Afterparty;

• Фотокарточкина память;

• И конечно, заряд хорошего настроения, новые знакомства и возможность прокачать свои скилы.

Доклады:
-------

<ul class="post-list">
{% for post in site.categories.talks %}
  {% if post.talk == "meetup_itf1" %}
    {% if post.author %}
      {% capture authorslist %}
        {% for a in post.author %}
          {% assign author = site.data.authors[a] %}
          {% if author %} {{ author.name }}{% if author.company %}, {{ author.company }}{% endif %}{% endif %}{% unless forloop.last %};{% endunless %}
        {% endfor %}
      {% endcapture %}
    {% endif %}
  {% if post.announce %}
  <li><img src="images/{{ author.avatar }}" class="bio-photo mainpage" alt="{{ author.name }} bio photo">
  <a href="{{ site.url }}{{ post.url }}">{{ authorslist }}<br/><b>{{ post.title }}</b><br/>
  <p class="micro-desc">{{ post.micro }}</p></a></li>
  {% endif %}
  {% endif %}
{% endfor %}
</ul>

Когда и где:
-----

__Вход – free__

Мы ждем тебя 21.02 в 18:30 в конференц-зале LOFT (г. Иваново, ул. Типографская, д. 6, 2 этаж).
Обязательна предварительная регистрация. Участие бесплатное.
Первые 30 зарегистрировавшихся получат повестку для явки на секретное AfterParty за счет компании.
Мы ждем тебя!

<a class="register-link__button" href="https://kompaniya-tenzor-events.timepad.ru/event/1247224/">Регистрация</a>

[place]: http://rybinsk.vikonda.ru/
[tensor]: http://tensor.ru/
[speakers]: /speakers/
[sbis]: https://sbis.ru/
[kltf]: http://kltf.tensor.ru/
[tmnconf]: http://tmnconf.tensor.ru/
[1070873]: https://kompaniya-tenzor-events.timepad.ru/event/1070873/
[1040266]: https://tensor-tmn.timepad.ru/event/1040266/
[1050019]: https://kompaniya-tenzor-events.timepad.ru/event/1050019/
[yarfrontend]: http://yarfrontend.ru/

[register]: https://kompaniya-tenzor-events.timepad.ru/event/1247224/