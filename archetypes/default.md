---
{{ $date := replace .File.Path "/" "-" | strings.TrimSuffix ".md" -}}
title: '{{ $date }}'
mood: Good
tags: []
---

# {{ $date }}

---
