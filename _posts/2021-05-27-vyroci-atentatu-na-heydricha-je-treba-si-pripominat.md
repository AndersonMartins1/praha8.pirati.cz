---
title: Výročí atentátu na Heydricha je třeba si připomínat
authorId: martin.sterba
date: 2021-05-27
image: posts/gros-mojeceskavlajka.png
tags: [Anthropoid]
fancybox:
  - name: Pietní akt 27. 5. 2021
    img:
      - { src: posts/anthropoid2021/anthropoid2021_01.jpg, title: Pietní akt 27. 5. 2021 }
      - { src: posts/anthropoid2021/anthropoid2021_02.jpg, title: Pietní akt 27. 5. 2021 }
      - { src: posts/anthropoid2021/anthropoid2021_03.jpg, title: Pietní akt 27. 5. 2021 }
      - { src: posts/anthropoid2021/anthropoid2021_04.jpg, title: Pietní akt 27. 5. 2021 }
      - { src: posts/anthropoid2021/anthropoid2021_05.jpg, title: Pietní akt 27. 5. 2021 }
      - { src: posts/anthropoid2021/anthropoid2021_06.jpg, title: Pietní akt 27. 5. 2021 }
      - { src: posts/anthropoid2021/anthropoid2021_07.jpg, title: Pietní akt 27. 5. 2021 }
      - { src: posts/anthropoid2021/anthropoid2021_08.jpg, title: Pietní akt 27. 5. 2021 }
      - { src: posts/anthropoid2021/anthropoid2021_09.jpg, title: Pietní akt 27. 5. 2021 }
      - { src: posts/anthropoid2021/anthropoid2021_10.jpg, title: Pietní akt 27. 5. 2021 }
      - { src: posts/anthropoid2021/anthropoid2021_11.jpg, title: Pietní akt 27. 5. 2021 }
      - { src: posts/anthropoid2021/anthropoid2021_12.jpg, title: Pietní akt 27. 5. 2021 }
      - { src: posts/anthropoid2021/anthropoid2021_13.jpg, title: Pietní akt 27. 5. 2021 }
      - { src: posts/anthropoid2021/anthropoid2021_14.jpg, title: Pietní akt 27. 5. 2021 }
---

**Předseda našeho místního sdružení [Martin Štěrba](https://praha8.pirati.cz/lide/martin-sterba.html) dnes společně se zástupci vedení městské části Praha 8, magistrátu, slovenské a britské ambasády a mnohými dalšími položil kytici k pomníku operace Anthropoid.**

Jsou historické momenty, které stojí za to si neustále připomínat. Mezi ně operace Anthropoid a atentát na zastupujícího říšského protektora Reinharda Heydricha, který se odehrál v zatáčce v ulici V Holešovičkách, bezesporu patří. Atentát provedli před 79 lety výsadkáři Jozef Gabčík a Jan Kubiš a svým příkladem ukázali, že Češi (a Slováci) umí být zkrátka i národem hrdinů! 🇨🇿

Čest jejich památce!

{% for galery in page.fancybox %}
<div class="mt-4">
  <h3>{{ galery.name }}</h3>
  <div class="grid grid-cols-4 gap-4">
  {% for item in galery.img %}
    <div class="">
      <a data-fancybox="gallery" href="{% asset '{{ item.src }}' @path %}" data-caption="{{ item.title }}">{% asset '{{ item.src }}' magick:resize='200x150^' magick:gravity='center' magick:crop='200x150+0+0' class="rounded" %}</a>
    </div>
  {% endfor %}
  </div>
</div>
{% endfor %}
