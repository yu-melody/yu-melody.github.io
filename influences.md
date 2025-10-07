---
layout: default
title: Influences
---

<div class="max-w-2xl mx-auto px-8 py-16">
    <h2 class="text-lg text-orange-950 mb-3">influences</h2>
    <p class="text-orange-800/80 mb-10 text-sm">
        Quotes and ideas that have shaped how I see the world.
    </p>
    <div class="space-y-8">
        {% for quote in site.data.quotes %}
        <div class="border-orange-400/60 border-l-2 pl-5 py-2 space-y-2">
            <p class="text-orange-900/90 italic leading-relaxed quote-text">
                "{{ quote.text }}"
            </p>
            <p class="text-sm text-orange-700/75">— {{ quote.source }}</p>
        </div>
        {% endfor %}
    </div>
</div>