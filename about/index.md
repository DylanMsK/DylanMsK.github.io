---
layout: page
title: About Me
tags: [about, Jekyll, theme, moon]
date: 2019-12-02
comments: false
---

# Who I am?
저 자신만의 성장보다는 함께 성장하여 서로의 단점을 보완하는 개발 문화를 지향합니다.

새로운 기술과 툴을 배우는 데 있어 두려움보다는 흥미가 앞서고, 겸손한 자세로 배워 나갑니다.

저의 개발 철학은 모든 사람에게 도움이 되는 서비스를 제작하는 것입니다.

<br>

---

<br>

# What I can use?
### Language
<div style="display:inline-flex;">
    <img src="{{ site.url }}/assets/img/logos/python.png" style="width:60px;height:60px;">
    <img src="{{ site.url }}/assets/img/logos/javascript.png" style="width:60px;height:60px;margin-left:2rem;">
</div>

### FrameWork
<div style="display:inline-flex;">
    <img src="{{ site.url }}/assets/img/logos/django.png" style="width:60px;height:60px;">
    <img src="{{ site.url }}/assets/img/logos/vuejs.png" style="width:60px;height:60px;margin-left:2rem;">
</div>

### Web Skills
<div style="display:inline-flex;">
    <img src="{{ site.url }}/assets/img/logos/javascript.png" style="width:60px;height:60px;">
    <img src="{{ site.url }}/assets/img/logos/html_css.png" style="width:100px;height:60px;margin-left:2rem;">
    <img src="{{ site.url }}/assets/img/logos/tailwind.jpg" style="width:60px;height:60px;margin-left:2rem;">
    <img src="{{ site.url }}/assets/img/logos/bootstrap.png" style="width:60px;height:60px;margin-left:2rem;">
</div>

### Database
<div style="display:inline-flex;">
    <img src="{{ site.url }}/assets/img/logos/postgresql.png" style="width:60px;height:60px;">
</div>

### Hosting
<div style="display:inline-flex;">
    <img src="{{ site.url }}/assets/img/logos/aws.png" style="width:70px;height:60px;">
    <img src="{{ site.url }}/assets/img/logos/firebase.png" style="width:60px;height:60px;margin-left:2rem;">
    <img src="{{ site.url }}/assets/img/logos/heroku.jpg" style="width:60px;height:60px;margin-left:2rem;">
    <img src="{{ site.url }}/assets/img/logos/netlify.png" style="width:60px;height:60px;margin-left:2rem;">
</div>

### Collaboration
<div style="display:inline-flex;">
    <img src="{{ site.url }}/assets/img/logos/github.png" style="width:60px;height:60px;">
    <img src="{{ site.url }}/assets/img/logos/jira.png" style="width:60px;height:60px;margin-left:2rem;">
    <img src="{{ site.url }}/assets/img/logos/slack.png" style="width:60px;height:60px;margin-left:2rem;">
    <img src="{{ site.url }}/assets/img/logos/trello.png" style="width:60px;height:60px;margin-left:2rem;">
</div>
<br>

---

<br>

# What I've done?

## Airbnb
에어비엔비의 핵심 기능을 Django 풀스택으로 구현한 서비스 입니다.<br>
유저는 게스트/호스트로 나누었으며, 게스트는 예약을 하고 호스트에게 메세지를 보내고 후기를 작성할 수 있습니다.<br>
호스트는 슈퍼 유저로서 예약을 관리하고 게스트에게 피드백을 보낼 수 있는 패널을 제공받습니다.

### 역할
* 백엔드: Python, Django, AWS ElasticBeantalk, AWS S3
* 프론트: HTML, CSS, Vanilla JS, Tailwind CSS, Gulp

![Airbnb 메인페이지]({{ site.url }}/assets/img/projects/airbnb/airbnb_main.png)

<br>

## Knocknock
근처 영업중인 요식업체 실시간 조회 서비스 입니다.<br>
유저는 클라이언트/파트너로 나누었으며, 클라이언트는 방문 희망하는 시간을 입력해 영업중인 인근 요식업체를 조회 가능합니다.<br>
파트너는 자신이 소유한 업체의 정보를 관리하며 특이사항 또는 이벤트 발생시 클라이언트에게 메세지/팝업을 전송합니다.

### 역할
* 백엔드: Python, Django, Pandas, AWS EC2, AWS RDS, Nginx

{% capture images %}
    {{ site.url }}/assets/img/projects/knocknock/restaurant_list.png
    {{ site.url }}/assets/img/projects/knocknock/restaurant_detail.png
    {{ site.url }}/assets/img/projects/knocknock/partner.png
{% endcapture %}
{% include gallery images=images caption="낰낰 웹 어플리케이션 스크린샷" cols=3 %}

<br>

## 당근마켓
당근마켓의 핵심 기능을 Django 풀스택으로 구현한 서비스 입니다.<br>
유저는 구매자/판매자로 나누었으며, 구매자는 판매자에게 채팅으로 거래를 신청하고 후기를 작성할 수 있습니다.<br>
판매자는 판매글을 작성하고 구매자들의 채팅에 피드백을 보낼 수 있습니다.

### 역할
* 백엔드: Python, Django, Heroku, AWS S3
* 프론트: HTML, CSS, JQuery, Bootstrap

![당근마켓 메인페이지]({{ site.url }}/assets/img/projects/daangn/daangn_main.png)

<br>

## Box.
국가별 박스오피스와 넷플릭스의 주간 랭킹을 조회하는 서비스 입니다.<br>
유저는 해당 영상에 대한 트레일러와 간단한 정보를 조회할 수 있습니다.

### 역할
* 백엔드: Python, Django, Selinium, Heroku
* 프론트: HTML, CSS, Vanilla JS, Bootstrap
