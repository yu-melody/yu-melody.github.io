---
layout: default
title: Experience
---

<div class="max-w-2xl mx-auto px-8 py-16">
    <h2 class="text-lg text-orange-950 mb-8">experience & lessons</h2>
    <div class="space-y-6">
        {% for exp in site.data.experiences %}
        <div class="space-y-1">
            <div class="text-orange-950">
                <span class="font-medium">{{ exp.company }}</span>
                <span class="text-orange-800/70"> — {{ exp.role }}</span>
            </div>
            <p class="text-orange-900/90 leading-relaxed">{{ exp.lesson }}</p>
        </div>
        {% endfor %}
    </div>
</div>