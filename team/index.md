---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team (2026)

{% include section.html %}

## Principal Investigator

{% include list.html data="members" component="portrait" filter="role == 'Principal Investigator'" %}

## Researchers & Graduate Students

{% include list.html data="members" component="portrait" filter="role == 'Postdoctoral Researcher'" %}
{% include list.html data="members" component="portrait" filter="role == 'PhD Student'" %}
{% include list.html data="members" component="portrait" filter="role == 'Master Student'" %}

## Research Assistants

{% include list.html data="members" component="portrait" filter="role == 'RA'" %}

## Alumni

{% include list.html data="members" component="portrait" filter="role == 'Alumni'" %}

{% include section.html background="images/background.jpg" dark=true %}

## Join Us!
연구실에서는 발달심리 연구에 직접 참여하는 경험을 쌓고 싶은, 성실하고 의욕 있는 학부생 연구 조교(Research Assistant)를 매 학기(1, 2학기 / 여름방학, 겨울방학) 모집하고 있습니다. 희망하는 학생들은 아래 링크를 통해 지원해주세요.
{% include button.html link="https://forms.gle/1x1hiVphYFNDJUcS7" text="학부생 RA 신청" icon="fa-solid fa-graduation-cap" %}

{% include section.html %}

## Lab photos

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
