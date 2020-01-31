---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

id: team
layout: default
title: Team
description:
slug: team
---

<!-- <div id="player" data-plyr-provider="vimeo" data-plyr-embed-id="331429597" data-vimeo-responsive="true" data-vimeo-autplay="true"></div> -->
<div class="page-header">
    <div class="page-header__content container">
        <h1 class="h5 page-label">{{ site.t.our_team }}</h1>
        <h2 class="h1 page-title">{{ site.t.leading_experts }}</h2>
    </div>
</div>
<article class="page-content">     
    <section class="page-section section-team-members container">
        {% assign ordered_team_members = site.team_members | sort: "order" %}
        {% for team_member in ordered_team_members %}
            {% assign id = team_member.first_name | replace: ' ', '-' | replace: '.', '' | downcase %}
            <div class="team-member row">
                <div class="team-member-img col" style="background-image: url('/assets/{{ team_member.img }}');">
                    <!-- <img src="/assets/{{ team_member.img }}" /> -->
                </div>
                <div class="team-member-bio col">
                    <div class="team-member-title">
                        <div>
                            <h2 class="team-member-name">{{ team_member.first_name }} {{ team_member.last_name }}</h2>
                            <p class="team-member-role">{{ team_member.title }}</p>
                        </div>
                        <a class="btn btn--icon" href="{{ team_member.linked_in_url }}" target="_blank"><svg class="icon" aria-title="LinkedIn Profile"><use xlink:href="/assets/site.svg#linkedin" /></svg></a>
                    </div>
                    {{ team_member.content | markdownify }}
                </div>
            </div>
        {% endfor %}
    </section>
</article>
