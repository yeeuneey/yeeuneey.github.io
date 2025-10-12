---
title: "수강 중인 강의"
summary: "현재(3학년 2학기) 수강 중인 강의"
type: landing
layout: list
---

현재 수강 중인 강의 목록입니다.

{{ range .Pages }}
- [{{ .Title }}]({{ .RelPermalink }})
{{ end }}