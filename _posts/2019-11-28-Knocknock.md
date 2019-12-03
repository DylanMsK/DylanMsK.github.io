---
layout: post
title:  "Knocknock"
date:   2019-11-28
excerpt: "근처 영업중인 요식업체 실시간 조회 서비스 입니다. 유저는 클라이언트/파트너로 나누었으며, 클라이언트는 방문 희망하는 시간을 입력해 영업중인 인근 요식업체를 조회 가능합니다. 파트너는 자신이 소유한 업체의 정보를 관리하며 특이사항 또는 이벤트 발생시 클라이언트에게 메세지/팝업을 전송합니다."
project: true
image: "knocknock/knocknock.png"
tag:
- Python
- Django
- PostgreSQL
- AWS
- Nginx
- Crawler
comments: false
---


<iframe width="560" height="315" src="//www.youtube.com/embed/QkY_2X8F-Jc" frameborder="0"></iframe>

<center><b>낰낰</b> 서비스 시연 영상</center>
     
## 서비스 개요
**낰낰(Knocknock)**은 근처 영업중인 요식업체 실시간 조회 서비스 입니다. 유저는 클라이언트/파트너로 나누었으며,<br>
클라이언트는 방문 희망하는 시간을 입력해 **영업중인 인근 요식업체를 조회하고 후기를 작성**합니다.<br>
파트너는 자신이 소유한 **업체의 정보를 관리하며 특이사항 또는 이벤트 발생시 클라이언트에게 공지**합니다.

<br>

## 프로젝트 기간
2019.10.14 - 2019.11.08

<br>

## 역할
백엔드 API 개발 및 AWS 배포

<br>

## 사용한 기술 스택
Python, Django, Pandas, Selinium, AWS, Nginx

<br>

## 주요 개발 내용
* Django Restframework를 이용한 **REST API** 개발
* 18만개의 요식업체 정보 수집 및 가공
* 데이터베이스 모델 설계 및 쿼리 최적화
* AWS 배포 및 서비스 유지/보수

<br>

## 미리보기

{% capture images %}
    {{ site.url }}/assets/img/projects/knocknock/restaurant_list.png
    {{ site.url }}/assets/img/projects/knocknock/restaurant_detail.png
{% endcapture %}
{% include gallery images=images caption="낰낰 클라이언트 어플리케이션 스크린샷" cols=2 %}

<br>

{% capture images %}
    {{ site.url }}/assets/img/projects/knocknock/partner.png
{% endcapture %}
{% include gallery images=images caption="낰낰 파트너 어플리케이션 스크린샷" cols=2 %}
