---
layout: post
title:  "Knocknock"
date:   2019-11-28
excerpt: "근처 영업중인 요식업체 실시간 조회 서비스 입니다. 그동안의 맛집 추천 서비스와는 다르게 '낰낰'은 지금 당장 열려있는 음식점과 카페를 보여줍니다."
project: true
image: "knocknock/knocknock.png"
tag:
- Python
- Django
- PostgreSQL
- AWS
- Nginx
comments: false
demo:     "https://client-knocknock.web.app/"
---

<center>
    <a href="https://client-knocknock.web.app/" class="btn" style="margin-bottom:2rem;">클라이언트 데모</a>
    <a href="https://partner-knocknock.web.app/" class="btn" style="margin-bottom:2rem;margin-left:2rem;">파트너 데모</a>
    <a href="https://getick.xyz/" class="btn" style="margin-bottom:2rem;margin-left:2rem;">API 문서</a>
</center>


<iframe width="560" height="315" src="//www.youtube.com/embed/QkY_2X8F-Jc" frameborder="0"></iframe>

<center><b>낰낰</b> 서비스 시연 영상</center>
     
## 서비스 개요
**낰낰(Knocknock)**은 근처 영업중인 요식업체 실시간 조회 서비스 입니다. 유저는 클라이언트/파트너로 나누었으며,<br>
클라이언트는 방문 희망하는 시간을 입력해 **영업중인 인근 요식업체를 조회**하고 후기를 작성합니다.<br>
파트너는 자신이 소유한 업체의 정보를 관리하며 특이사항 또는 이벤트 발생시 **클라이언트에게 공지**합니다.

<br>

## 프로젝트 기간
2019.10.14 - 2019.11.08

<br>

## 프로젝트 목표
* 데이터 필터링 조건에 **시간**과 **위치** 조건을 최우선으로 한다.
* **법정 공휴일** 및 **임시 휴무일** 등의 특정 이벤트를 고려해 DB를 설계한다.
* 위/경도와 주소등의 **지리정보에 최적화**된 Query를 설계한다.
* **HTTPS를 적용**해 third-party 앱과 호환 가능하게 한다.

<br>

## 담당 역할
백엔드 API 개발 및 AWS 배포

<br>

## 사용한 기술 스택
`Python`, `Django`, `Pandas`, `AWS`, `Nginx`

<br>

## 주요 개발 내용
* Django Restframework를 이용한 **REST API** 개발
* **18만개**의 요식업체 정보 수집 및 가공
* 데이터베이스 **모델 설계 및 쿼리 최적화**
* **AWS** 배포 및 서비스 유지/보수

<br>

## 미리보기
### 클라이언트 어플리케이션 스크린샷
{% capture images %}
    {{ site.url }}/assets/img/projects/knocknock/restaurant_list.png
    {{ site.url }}/assets/img/projects/knocknock/restaurant_detail.png
{% endcapture %}
{% include gallery images=images caption="낰낰 클라이언트앱 스크린샷" cols=2 %}

<br>

### 파트너 어플리케이션 스크린샷
{% capture images %}
    {{ site.url }}/assets/img/projects/knocknock/partner_restaurant_list.png
    {{ site.url }}/assets/img/projects/knocknock/partner_restaurant_detail.png
{% endcapture %}
{% include gallery images=images caption="낰낰 파트너앱 스크린샷" cols=2 %}

<center>
    <a href="https://client-knocknock.web.app/" class="btn" style="margon-top:3rem;margin-bottom:2rem;">클라이언트 데모</a>
    <a href="https://partner-knocknock.web.app/" class="btn" style="margon-top:3rem;margin-bottom:2rem;margin-left:2rem;">파트너 데모</a>
    <a href="https://getick.xyz/" class="btn" style="margon-top:3rem;margin-bottom:2rem;margin-left:2rem;">API 문서</a>
</center>