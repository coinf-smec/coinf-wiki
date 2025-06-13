---
layout: default
title: Página Inicial
---

# 👋 Bem-vindo

Este é o portal oficial da **Coordenação de Informática – SMEC**.  
Aqui você encontrará tutoriais, scripts e orientações técnicas utilizadas em nossa rede.

## 📝 Tutoriais Recentes

{% for post in site.posts limit:5 %}
- 📌 [{{ post.title }}]({{ post.url }}) – _{{ post.date | date: "%d/%m/%Y" }}_
{% endfor %}

---
🔐 *Acesso técnico restrito à equipe autorizada.*
