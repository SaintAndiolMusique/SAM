---
layout: default
title: Accueil
---

# Bienvenue sur le site de Saint Andiol Musique - SAM🌟

![Logo de l'association](assets/images/logo.png){: style="max-width: 300px; margin: 20px auto; display: block;"}

Nous sommes une association engagée pour soutenir, animer et fédérer autour de la musique, sans besoin d’être musicien pour nous rejoindre !. Découvrez notre travail, nos actualités et comment nous rejoindre !

## 📢 Dernières Actualités

<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - <small>{{ post.date | date: "%d %B %Y" }}</small>
      <p>{{ post.excerpt | strip_html | truncatewords: 20 }}</p>
    </li>
  {% endfor %}
</ul>

<a href="news" class="button">Voir toutes les actualités</a>

---

## 🎯 Notre Mission



> "Notre objectif est de Nos actions
 - Location d’instruments aux élèves débutants, pour découvrir la musique sans investissement lourd.
 - Sorties culturelles : visites d’opéras, concerts, soirées à thème pour explorer l’univers musical.
 - Animation des événements de l’école de musique : buvettes, tombolas, temps conviviaux.
 - Accueil des idées : vos propositions sont les bienvenues !"
---

## 📞 Contacte-nous

📧 **Email** : [contact@ton-association.fr](mailto:contact@ton-association.fr)
📍 **Adresse** : [Ton adresse physique, si applicable]
🌐 **Site web** : [https://ton-username.github.io](https://ton-username.github.io)

<a href="contact" class="button">Nous envoyer un message</a>
