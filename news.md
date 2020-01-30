---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

id: news
layout: default
title: News
description: 
slug: news
---
<!-- <div id="player" data-plyr-provider="vimeo" data-plyr-embed-id="331429597" data-vimeo-responsive="true" data-vimeo-autplay="true"></div> -->
<div class="page-header">
    <div class="page-header__content container">
        <h1 class="h4 page-label">{{ site.t.news }}</h1>
        <h2 class="h1 page-title">{{ site.t.press_releases_news_articles }}</h2>
    </div>
</div>
<article class="page-content container"> 
    <div class="page-section">    
    {% assign ordered_news_items = site.news | sort: "date" | reverse %}
    {% for news_item in ordered_news_items %}
        <div class="news-item">
            <h2 class="news-item-title">{{ news_item.title }}</h2>
            <p class="news-item-date">{{ news_item.date | date: "%B %d, %Y" }} &middot; {{ news_item.location }}</p>
            {{ news_item.content | markdownify }}

            <h3>About Bostel Technologies</h3>                                                                                                                            
            <p>Bostel Technologies LLC is a privately-held, Boston-headquartered medical technology company that has created a patented diagnostic platform called Melody™ that uses Dual Deep Learning technology to improve the clinical diagnoses of melanoma by applying an additional sonification (data to sound waves conversion) layer on deep learning algorithms.</p>
            <p>For more information please visit <a href="https://www.BostelTechnologies.com">https://www.BostelTechnologies.com</a>.</p>
            <p>Contact:  <strong>Harry Keegan</strong>, CEO: XXXX</p>
        </div>
    {% endfor %}
    </div>
</article>
