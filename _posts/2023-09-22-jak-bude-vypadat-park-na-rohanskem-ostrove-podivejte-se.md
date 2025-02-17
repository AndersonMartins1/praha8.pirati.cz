---
title: "Jak bude vypadat nový park na Rohanském ostrově? Podívejte se"
author: Piráti Praha 8
image: posts/vizualizace/park-rohansky-ostrov/Rohan4.jpg
tags: [Park Maniny, Životní prostředí, IPR, Rohanský ostrov]
fancybox:
  - name: Vizualizace nového parku na Rohanském ostrově
    img:
      - { src: posts/vizualizace/park-rohansky-ostrov/Rohan1.jpg, title: Vítězný návrh parku (OMGEVING+FISER+VRV+SINDLAR (BE/CZ)) }
      - { src: posts/vizualizace/park-rohansky-ostrov/Rohan2.jpg, title: Vítězný návrh parku (OMGEVING+FISER+VRV+SINDLAR (BE/CZ)) }
      - { src: posts/vizualizace/park-rohansky-ostrov/Rohan3.jpg, title: Vítězný návrh parku (OMGEVING+FISER+VRV+SINDLAR (BE/CZ)) }
      - { src: posts/vizualizace/park-rohansky-ostrov/Rohan4.jpg, title: Vítězný návrh parku (OMGEVING+FISER+VRV+SINDLAR (BE/CZ)) }
      - { src: posts/vizualizace/park-rohansky-ostrov/Rohan5.jpg, title: Vítězný návrh parku (OMGEVING+FISER+VRV+SINDLAR (BE/CZ)) }
      - { src: posts/vizualizace/park-rohansky-ostrov/Rohan6.jpg, title: Vítězný návrh parku (OMGEVING+FISER+VRV+SINDLAR (BE/CZ)) }
---

**Na území 56 hektarů vznikne povodňový park, který propojí člověka s řekou, zachová tamní biodiverzitu a efektivně přispěje k protipovodňové ochraně města.**

>"Holešovický meandr je unikátním přírodním jevem. V rámci Pražské kotliny i celých Čech. Na celém toku Vltavy nenajdeme podobný prostor takto velkoryse utvářený v tak náhlém kontrastu k hluboce sevřeným kaňonům na jih i sever od Prahy. Sílu původního krajinného obrazu zásadně přetvořeného regulací říčního koryta navrhujeme připomenout kouskem "mezivodí" po letech opět definovaného dynamickým rytmem řeky. Nabízíme hybridní prostorovou mozaiku nepředurčených příběhů pokaždé prožívaných trochu jinak," píše [Institut plánování a rozvoje hl. města Prahy na svém webu](https://iprpraha.cz/projekt/38/rohansky-ostrov).

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
<br/>

Na tento a dalších dvacet čtyři projektů se můžete těšit v nové výstavě v CAMP - Centrum architektury a městského plánování, která začne 22. 9. 2023 slavnostní vernisáží. Výsledkům soutěžního dialogu se v CAMP věnuje i samostatná expozice v Bílém sále. Najdete zde návrhy 4 soutěžních týmů a vyjádření poroty, které přiblíží, jak byly návrhy hodnoceny a v čem spočívá jejich kvalita.

<div class="inline-flex flex-col sm:flex-row space-y-8 sm:space-y-0 sm:space-x-8">
  <div class="inline-flex flex-col space-y-2">
    <span class="alert alert--black">
      <i class="alert__icon ico--pirati"></i>
      <span><b>Hodnocení komise</b><br />Vítězný tým představil velmi přesvědčivý a proveditelný návrh parku, který je mimořádně inovativní v přístupu řešení protipovodňové ochrany. Návrh zvítězil díky vyváženosti nabídky - vysoce kvalitnímu, srozumitelnému a dobře proveditelnému návrhu, efektivitě navrhovaného procesu a výhodné cenové nabídce. </span>
    </span>
  </div>
</div>

### Co je to vlastně park Maniny?
> Park Maniny, povodňový park na řece Vltavě, je jedním z posledních velkých projektů, který má potenciál zlepšit protipovodňovou ochranu v Praze. Původní projekt vzniku nového kanálu, který měl již několik let stavební povolení, byl právě v rámci soutěžního dialogu prověřován. Vítězný návrh dokázal najít vhodnější a efektivnější přístup k území, a to v kontextu současných majetkoprávních vztahů a za dostupných finančních prostředků. Počítá s výrazně nižšími odkopy terénu, tedy i s nižšími náklady na realizaci, přičemž efektivita protipovodňového opatření je zachována. Spolu se stavbou libeňského inundačního (povodňového) mostu se tak naplní funkce protipovodňové ochrany území, které poskytne větší plochu pro rozliv vody a zpomalí proud řeky během povodní. Území Rohanského ostrova je poslední místo v Praze, kde se dá protipovodňová ochrana centra města významně zlepšit.

[Další informace najdete přímo na webu Institut plánování a rozvoje hlavního města Prahy.](https://iprpraha.cz/projekt/38/rohansky-ostrov)
