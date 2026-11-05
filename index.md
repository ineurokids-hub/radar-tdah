---
layout: default
title: Início
---

# Radar TDAH na Prática

Todo dia de manhã, este radar lê dezenas de notícias e pesquisas sobre TDAH, aqui e lá fora, e separa só o que vale a pena para quem cuida de uma criança ou adolescente com TDAH. Tudo explicado em português simples, com o link da fonte original.

Curadoria: **Dr. Fábio Baiocco**, neurologista infantil.

## Radares mais recentes <a class="rss-icon" href="{{ '/feed-pt.xml' | relative_url }}" aria-label="Assinar por RSS"><svg viewBox="0 0 448 512" xmlns="http://www.w3.org/2000/svg"><path fill="currentColor" d="M128.081 415.959c0 35.369-28.672 64.041-64.041 64.041S0 451.328 0 415.959s28.672-64.041 64.041-64.041 64.04 28.673 64.04 64.041zm175.66 47.25c-8.354-154.6-132.185-278.587-286.95-286.95C7.656 175.765 0 183.105 0 192.253v48.069c0 8.415 6.49 15.472 14.887 16.018 111.832 7.284 201.473 96.702 208.772 208.772.547 8.397 7.604 14.887 16.018 14.887h48.069c9.149.001 16.489-7.655 15.995-16.79zm144.249.288C439.596 229.677 251.465 40.445 16.503 32.01 7.473 31.686 0 38.981 0 48.016v48.068c0 8.625 6.835 15.645 15.453 15.999 191.179 7.839 344.627 161.316 352.465 352.465.353 8.618 7.373 15.453 15.999 15.453h48.068c9.034-.001 16.329-7.474 16.005-16.504z"/></svg></a>

<ul>
  {% assign pt_posts = site.posts | where: "lang", "pt" %}
  {% for post in pt_posts limit:30 %}
    <li>
      <a href="{{ post.url | relative_url }}">Radar de {{ post.date | date: "%d/%m/%Y" }}</a>
    </li>
  {% else %}
    <li><em>O primeiro radar sai amanhã cedo.</em></li>
  {% endfor %}
</ul>

---

<small>Este radar é informativo e não substitui a consulta. Nenhuma mudança de tratamento ou de dose deve ser feita sem conversar com o médico que acompanha a criança.</small>
