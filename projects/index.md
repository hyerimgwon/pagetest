---
title: Projects
nav:
  order: 2
  tooltip: What we study
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

진행 중인 연구 목록입니다. 해당 포스터를 클릭하시면 참여 링크로 이동합니다.

{% include tags.html tags="영아, 유치원생, 초등학생" %}

{% include button.html type="link" icon="fa-solid fa-flask" text="연구과제 목록 보기" link="https://fis.yonsei.ac.kr/faculty/member.do?mode=view&userId=KO9d8%2F04eIG9m4Eb2dU2LA%3D%3D&sosokcd=0000142" %}

{% include search-info.html %}

{% include section.html %}

## 진행 중인 연구 Ongoing

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## 지난 연구 Completed

{% include list.html component="card" data="projects" filter="!group" style="small" %}
