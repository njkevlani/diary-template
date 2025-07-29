---
{{ $date := replace .File.Path "/" "-" | strings.TrimSuffix ".md" -}}
title: '{{ $date }}'
date: '{{ $date }}'
mood: Good
tags: []
---

# {{ $date }}

---
