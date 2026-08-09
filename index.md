---
---

# 안녕하세요, 연세대학교 발달심리 연구실입니다! 😊

<div style="text-align: center;">
  
아기들은 태어나자마자 자신을 둘러싼 새로운 세상에 대해 수없이 많은 것들을 배워 나가기 시작합니다. <br>
저희 연구실은 아기들이 세상과 언어를 어떻게 이해하고 배우는지를 연구하고 있습니다. <br>
연구는 인형극 무대나 비디오 시청, 게임 형식으로 이루어져 아이들이 즐겁게 참여할 수 있으며, <br>
​모든 절차는 부모님의 동의 하에 안전히 진행됩니다. <br><br>
{% include button.html link="https://docs.google.com/forms/d/e/1FAIpQLScduYahK5CUcUga4La3XH4SX-jf716GfPfj_vMu8CYJ8Vwmow/viewform" text="연구 참여 신청" icon="fa-solid fa-child-reaching" %}
{% include button.html link="https://forms.gle/1x1hiVphYFNDJUcS7" text="학부생 RA 신청" icon="fa-solid fa-graduation-cap" %}

</div>

{% include section.html %}

## Highlights

{% capture text %}

저희 연구실은 인지발달, 언어 발달, 심리추론 능력 이해 발달, 도덕성 발달, 그리고 노인기의 인지 및 정서 발달 등 인간 발달의 다양한 측면을 탐구합니다. 특히 최근에는 아동의 호기심과 질문 능력의 발달에 대해 탐구하고 있습니다.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/curiosity.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

저희 연구실에서는 여러 연구가 동시에 진행되고 있으며, 각 연구에 참여할 아동과 부모님을 모집하고 있습니다. 모집 연령과 연구 주제를 확인하신 뒤 해당 링크를 눌러 자세한 안내를 읽어보실 수 있습니다. 지금 아이의 연령에 맞는 연구가 없더라도 신청해 주세요. 연령에 맞는 연구가 개설되면 연락드리겠습니다.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/ourproject.jpeg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

발달심리 연구실은 지도교수를 비롯한 여러 연구원들이 함께 아이들의 마음을 들여다보고 있습니다. 발달심리에 관심 있는 분이라면 언제든 함께할 수 있습니다.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/team.jpg"
  link="team"
  title="Our Team"
  text=text
%}

<style>
header img {
  height: clamp(180px, 10vw, 360px) !important;
  width: auto !important;
}
header .title {
  font-size: clamp(1.5rem, 5vw, 3rem) !important;
}
header .subtitle {
  font-size: clamp(1rem, 3vw, 1.7rem) !important;
}
main h1 {
  font-family: 'AyoungSYearning2019Handwriting', 'Pretendard Variable', sans-serif !important;
  font-weight: 400 !important;
  line-height: 1.4 !important;
}
header {
  padding-top: 2rem !important;
  padding-bottom: 2rem !important;
  min-height: 0 !important;
}
</style>
