---
title: "{{ substr .TranslationBaseName 8 2 }}-{{ substr .TranslationBaseName 16 2}}"
imgsrc: "/img/journal/{{substr .TranslationBaseName 0 4}}/{{substr .TranslationBaseName 5  2}}/{{substr .TranslationBaseName 8 2}}-{{substr .TranslationBaseName 19 2}}.jpg"
date: {{ substr .TranslationBaseName 0 10 }}
enddate: {{ substr .TranslationBaseName 11 10 }}
draft: false
---

<!-- fix pre-formatted input -->
