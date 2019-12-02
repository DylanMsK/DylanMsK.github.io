---
layout: post
title:  "Knocknock"
date:   2019-11-28
excerpt: "근처 영업중인 요식업체 실시간 조회 서비스"
project: true
image: "django.png"
tag:
- Python
- Django
- PostgreSQL
- AWS
- Nginx
- Crawler
comments: false
---

<iframe width="560" height="315" src="//www.youtube.com/watch?v=QkY_2X8F-Jc" frameborder="0"></iframe>

<center><b>[낰낰](https://client-knocknock.web.app/)</b> 서비스 시연 영상.</center>
     
## 서비스 개요
**낰낰(Knocknock)** 은 근처 영업중인 요식업체 실시간 조회 서비스 입니다.<br>
유저는 클라이언트/파트너로 나누었으며, 클라이언트는 방문 희망하는 시간을 입력해 영업중인 인근 요식업체를 조회하고 후기를 작성합니다.<br>
파트너는 자신이 소유한 업체의 정보를 관리하며 특이사항 또는 이벤트 발생시 클라이언트에게 메세지/팝업을 전송합니다.

<br>

## 담당 역할
* 백엔드: Python, Django, Pandas, AWS EC2, AWS RDS, Nginx

<br>

## 주요 개발 내용
* Django Restframework를 이용한 REST API 개발
* 18만개의 요식업체 정보 수집 및 가공
* DB 모델 설계 및 쿼리 최적화
* AWS EC2 배포 및 서비스 유지/보수

<br>

## 사용된 기술 스택
* Fork the [Moon repo](https://github.com/TaylanTatli/Moon/fork)
* Edit `_config.yml` file.
* Remove sample posts from `_posts` folder and add yours.
* Edit `index.md` file in `about` folder.
* Change repo name to `YourUserName.github.io`    
     
That's all.

## 미리보기

{% capture images %}
    {{ site.url }}/assets/img/projects/knocknock/restaurant_list.png
    {{ site.url }}/assets/img/projects/knocknock/restaurant_detail.png
    {{ site.url }}/assets/img/projects/knocknock/partner.png
{% endcapture %}
{% include gallery images=images caption="낰낰 웹 어플리케이션 스크린샷" cols=3 %}

---

{% capture images %}
	https://cloud.githubusercontent.com/assets/754514/14509718/61b09a20-01d6-11e6-8da1-4202ae4d83cd.png
	https://cloud.githubusercontent.com/assets/754514/14509715/61aa9d00-01d6-11e6-81a6-c6837edf2e84.png
{% endcapture %}
{% include gallery images=images caption="Moon Theme on Small Screen Size" cols=2 %}      
      
See a [live version of Moon](http://taylantatli.github.io/Moon) hosted on GitHub.      

## Site Setup
A quick checklist of the files you’ll want to edit to get up and running.    

### Site Wide Configuration
`_config.yml` is your friend. Open it up and personalize it. Most variables are self explanatory but here's an explanation of each if needed:

#### title

The title of your site... shocker!

Example `title: My Awesome Site`

#### bio

The description to show on your homepage.

#### description

The description to use for meta tags and navigation menu.

#### url

Used to generate absolute urls in `sitemap.xml`, `feed.xml`, and for generating canonical URLs in `<head>`. When developing locally either comment this out or use something like `http://localhost:4000` so all assets load properly. *Don't include a trailing `/`*.

Examples:

{% highlight yaml %}
url: http://taylantatli.me/Moon
url: http://localhost:4000
url: //cooldude.github.io
url:
{% endhighlight %}

#### reading_time

Set true to show reading time for posts. And set `words_per_minute`, default is 200.

#### logo
Your site's logo. It will show on homepage and navigation menu. Also used for twitter meta tags.

#### background
Image for background. If you don't set it, color will be used as a background.

#### Google Analytics and Webmaster Tools

Google Analytics UA and Webmaster Tool verification tags can be entered in `_config.yml`. For more information on obtaining these meta tags check [Google Webmaster Tools](http://support.google.com/webmasters/bin/answer.py?hl=en&answer=35179) and [Bing Webmaster Tools](https://ssl.bing.com/webmaster/configure/verify/ownership) support.

#### MathJax
It's enabled. But if you don't want to use it. Set it false in  `_config.yml`.

#### Disqus Comments
Set your disqus shortname in `_config.yml` to use comments.

---

### Navigation Links

To set what links appear in the top navigation edit `_data/navigation.yml`. Use the following format to set the URL and title for as many links as you'd like. *External links will open in a new window.*

{% highlight yaml %}
- title: Home
  url: /

- title: Blog
  url: /blog/

- title: Projects
  url: /projects/

- title: About
  url: /about/

- title: Moon
  url: http://taylantatli.me/Moon
{% endhighlight %}

---

## Layouts and Content

Moon Theme use [Jekyll Compress](https://github.com/penibelst/jekyll-compress-html) to compress html output. But it can cause errors if you use "linenos" (line numbers). I suggest don't use line numbers for codes, because it won't look good with this theme, also i didn't give a proper style for them. If you insist to use line numbers, just remove `layout: compress` string from layouts. It will disable compressing.

### Feature Image

You can set feature image per post. Just add `feature: some link` to your post's front matter.

```
feature: /assets/img/some-image.png
or
feaure: http://example.com/some-image.png
```    
 This also will be used for twitter card:

![Moon Twitter Card](https://cloud.githubusercontent.com/assets/754514/14509719/61c5751c-01d6-11e6-8c29-ce8ccad149bf.png)

### Comments
To show disqus comments for your post add `comments: true` to your post's front matter.

---

## Questions?

Found a bug or aren't quite sure how something works? By all means [file a GitHub Issue](https://github.com/TaylanTatli/Moon/issues/new). And if you make something cool with this theme feel free to let me know.

---

## License

This theme is free and open source software, distributed under the MIT License. So feel free to use this Jekyll theme on your site without linking back to me or including a disclaimer.
