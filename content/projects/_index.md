---
title: Projects
type: landing

sections:
  - block: collection
    content:
      title: ""
      count: 10
      filters:
        taxonomy: project_types   # ✅ 아까 정의한 taxonomy
        show: true                # ✅ 필터바 보이기
        show_all: true
        folders:
          - projects     # ✅ projects 폴더만 가져오기
        exclude_featured: false
    design:
      view: card
      columns: '2' # 2열 고정
---
