---
layout: page
title: About Me
tags: [about, Jekyll, theme, moon]
date: 2019-12-02
comments: false
---

# Who I am?
<p style="font-size:1.2rem;">
동료와 함께 성장하는 개발 문화를 지향합니다.
</p>
<p style="font-size:1.2rem;">
새로운 것에 두려움 보다는 흥미가 앞서고, 겸손한 자세로 배워 나갑니다.
</p>
<p style="font-size:1.2rem;">
저의 개발 철학은 모든 사용자가 편리하게 사용할 수 있는 서비스를 제작하는 것입니다.
</p>

<br>

---

<br>

# What I can use?
### 프로그래밍 언어
<div style="display:inline-flex;">
    <img src="{{ site.url }}/assets/img/logos/python.png" style="width:60px;height:60px;">
</div>

### 프레임워크
<div style="display:inline-flex;">
    <img src="{{ site.url }}/assets/img/logos/django.png" style="width:60px;height:60px;">
    <img src="{{ site.url }}/assets/img/logos/vuejs.png" style="width:60px;height:60px;margin-left:2rem;">
</div>

### 프론트 기술
<div style="display:inline-flex;">
    <img src="{{ site.url }}/assets/img/logos/javascript.png" style="width:60px;height:60px;">
    <img src="{{ site.url }}/assets/img/logos/html_css.png" style="width:100px;height:60px;margin-left:2rem;">
    <img src="{{ site.url }}/assets/img/logos/tailwind.jpg" style="width:60px;height:60px;margin-left:2rem;">
    <img src="{{ site.url }}/assets/img/logos/bootstrap.png" style="width:60px;height:60px;margin-left:2rem;">
</div>

### 데이터베이스
<div style="display:inline-flex;">
    <img src="{{ site.url }}/assets/img/logos/postgresql.png" style="width:60px;height:60px;">
</div>

### 호스팅 서비스
<div style="display:inline-flex;">
    <img src="{{ site.url }}/assets/img/logos/aws.png" style="width:70px;height:60px;">
    <img src="{{ site.url }}/assets/img/logos/firebase.png" style="width:60px;height:60px;margin-left:2rem;">
    <img src="{{ site.url }}/assets/img/logos/heroku.jpg" style="width:60px;height:60px;margin-left:2rem;">
    <img src="{{ site.url }}/assets/img/logos/netlify.png" style="width:60px;height:60px;margin-left:2rem;">
</div>

### 협업 툴
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

## [Knocknock]({{ site.url }}/Knockonck)
근처 영업중인 요식업체 실시간 조회 서비스 입니다.<br>
유저는 클라이언트/파트너로 나누었으며, 클라이언트는 방문 희망하는 시간을 입력해 영업중인 인근 요식업체를 조회 가능합니다.<br>
파트너는 자신이 소유한 업체의 정보를 관리하며 특이사항 또는 이벤트 발생시 클라이언트에게 메세지/팝업을 전송합니다.

### 역할
* 백엔드: `Python`, `Django`, `Pandas`, `AWS EC2`, `AWS RDS`, `Nginx`

{% capture images %}
    {{ site.url }}/assets/img/projects/knocknock/restaurant_list.png
    {{ site.url }}/assets/img/projects/knocknock/restaurant_detail.png
{% endcapture %}
{% include gallery images=images caption="낰낰 웹 어플리케이션 스크린샷" cols=3 %}

---

## [Getick]({{ site.url }}/Getick)
매진된 SRT 티켓을 자동 예매 해주는 서비스 입니다.<br>
사용자는 희망하는 날짜와 시간을 입력하며, 해당 시간에 취소표가 발생시 자동으로 예매를 진행해 사용자에게 문자/메일을 전송합니다.

### 역할
* 백엔드: `Python`, `Django`, `Heroku`
* 프론트엔드: `Vus.js`, `Vuetify`, `Firebase`

<br>

---

## [Airbnb]({{ site.url }}/Airbnb)
에어비엔비의 핵심 기능을 Django 풀스택으로 구현한 서비스 입니다.<br>
유저는 게스트/호스트로 나누었으며, 게스트는 예약을 하고 호스트에게 메세지를 보내고 후기를 작성할 수 있습니다.<br>
호스트는 슈퍼 유저로서 예약을 관리하고 게스트에게 피드백을 보낼 수 있는 패널을 제공받습니다.

### 역할
* 백엔드: `Python`, `Django`, `AWS ElasticBeantalk`, `AWS S3`
* 프론트: `HTML`, `CSS`, `Vanilla JS`, `Tailwind CSS`, `Gulp`

![Airbnb 메인페이지]({{ site.url }}/assets/img/projects/airbnb/airbnb_main.png)

<br>

---

## [당근마켓]({{ site.url }}/Daangn)
당근마켓의 핵심 기능을 Django 풀스택으로 구현한 서비스 입니다.<br>
유저는 구매자/판매자로 나누었으며, 구매자는 판매자에게 채팅으로 거래를 신청하고 후기를 작성할 수 있습니다.<br>
판매자는 판매글을 작성하고 구매자들의 채팅에 피드백을 보낼 수 있습니다.

### 역할
* 백엔드: `Python`, `Django`, `Heroku`, `AWS S3`
* 프론트: `HTML`, `CSS`, `JQuery`, `Bootstrap`

![당근마켓 메인페이지]({{ site.url }}/assets/img/projects/daangn/daangn_main.png)

<br>

---

## [Box.]({{ site.url }}/Box)
국가별 박스오피스와 넷플릭스의 주간 랭킹을 조회하는 서비스 입니다.<br>
유저는 해당 영상에 대한 트레일러와 간단한 정보를 조회할 수 있습니다.

### 역할
* 백엔드: `Python`, `Django`, `Selinium`, `Heroku`
* 프론트: `HTML`, `CSS`, `Vanilla JS`, `Bootstrap`

![Box 국가 리스트]({{ site.url }}/assets/img/projects/box/movie_detail1.png)

<br>

---

<br>

# Contact
## 이름: 강민수
## 이메일: kms920612@gmail.com
