---
---

# 안녕하세요, 연세대학교 발달심리 연구실입니다! 😊

<div style="text-align: center;">
  
아기들은 태어나자마자 자신을 둘러싼 새로운 세상에 대해 수없이 많은 것들을 배워 나가기 시작합니다. <br>
저희 연구실은 아기들이 세상과 언어를 어떻게 이해하고 배우는지를 연구하고 있습니다. <br>
연구는 인형극 무대나 비디오 시청, 게임 형식으로 이루어져 아이들이 즐겁게 참여할 수 있으며, <br>
​모든 절차는 부모님의 동의 하에 안전히 진행됩니다.

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

현재 진행 중인 연구들과 참여 가능한 연구들 써두면 될듯?

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

발달심리 연구실의 귀염둥이 구성원들을 소개합니다 뿌뿌

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
  image="images/photo.jpg"
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
  font-size: clamp(1.5rem, 5vw, 3.2rem) !important;
}
header .subtitle {
  font-size: clamp(1rem, 3vw, 2rem) !important;
}
main h1 {
  font-family: 'AyoungSYearning2019Handwriting', 'Pretendard Variable', sans-serif !important;
  font-weight: 400 !important;
  line-height: 1.4 !important;
}
</style>
