---
{{ $date := replace .File.Path "/" "-" | strings.TrimSuffix "-_index.md" -}}
title: '{{ $date }}'
tags: []
---

# {{ $date }}
