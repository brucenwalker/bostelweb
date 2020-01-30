---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

id: home
layout: default
description: 
---
<!-- <div id="player" data-plyr-provider="vimeo" data-plyr-embed-id="331429597" data-vimeo-responsive="true" data-vimeo-autplay="true"></div> -->
<div class="page-header">
    <div class="page-header__content container">
        <h1 class="h4 page-label">A NEW FRONTIER</h1>
        <h2 class="h1 page-title">{{ site.t.diagnosing_skin_cancer_melody }}</h2>
        <a href="#" class="btn btn--lg">{{ site.t.learn_more }}</a>
    </div>
    <!-- <a href="#programs" class="discover-more-btn">
        <span class="label">{{ site.t.learn_more }}</span>
        <span class="line">
            <span class="line-inner"></span>
        </span>
    </a> -->
</div>
<article class="page-content">     
    <!-- <section class="page-section section-jobs container">
        <div class="row">
            <div class="col">
                <div class="h4">{{ site.t.upskill_for_better_future }}</div>
                <h2>{{ site.t.jobs_with_meaning }}</h2>
                <img class="hide-sm" src="/assets/app-store-outline.svg" alt="{{ site.t.coming_soon_ios }}" />
                <img class="hide-sm" src="/assets/google-play.svg" alt="{{ site.t.coming_soon_android }}" />
            </div>
            <div class="col ml-md-5 pt-md-2 txt-md-center">
                {{ site.t.jobs_content | 'html' }}
                <img class="hide-md mb-1" src="/assets/app-store-outline.svg" alt="{{ site.t.coming_soon_ios }}" />
                <img class="hide-md mb-1" src="/assets/google-play.svg" alt="{{ site.t.coming_soon_android }}" />
            </div>
        </div>
    </section>
    <section id="programs" class="page-section section-courses container container--wide">
        <h2 class="section-title">{{ site.t.our_caregiving_programs }}</h2>
        <div class="courses courses-container">
            <div id="course-introduction" class="course">
                <div class="h4 course__subtitle">{{ site.t.basics }}</div>
                <h3 class="course__title">{{ site.t.introduction }}</h3>
                <p class="course__desc">{{ site.t.intro_content }}</p>
                <a href="/contact/" class="btn get-started-btn">{{ site.t.get_started }}</a>
            </div>
            <div id="course-fundamentals" class="course">
                <div class="h4 course__subtitle">{{ site.t.beginner }}</div>
                <h3 class="course__title">{{ site.t.fundamentals }}</h3>
                <p class="course__desc">{{ site.t.fundamentals_content }}</p>
                <a href="/contact/" class="btn get-started-btn">{{ site.t.get_started }}</a>
            </div>
            <div id="course-care-safety" class="course">
                <div class="h4 course__subtitle">{{ site.t.advanced }}</div>
                <h3 class="course__title">{{ site.t.care_safety }}</h3>
                <p class="course__desc">{{ site.t.care_safety_content }}</p>
                <a href="/contact/" class="btn btn--info get-started-btn">{{ site.t.coming_soon }}</a>
            </div>
            <div id="course-related-conditions" class="course">
                <div class="h4 course__subtitle">{{ site.t.advanced }}</div>
                <h3 class="course__title">{{ site.t.age_related_conditions }}</h3>
                <p class="course__desc">{{ site.t.age_related_content }}</p>
                <a href="/contact/" class="btn btn--info get-started-btn">{{ site.t.coming_soon }}</a>
            </div>
            <div id="course-complex-care" class="course">
                <div class="h4 course__subtitle">{{ site.t.expert }}</div>
                <h3 class="course__title">{{ site.t.complex_care }}</h3>
                <p class="course__desc">{{ site.t.complex_care_content }}</p>
                <a href="/contact/" class="btn btn--info get-started-btn">{{ site.t.coming_soon }}</a>
            </div>
        </div>
    </section>
    <section id="about" class="page-section section-is-for">
        <div class="container">
            <h2>{{ site.t.care_campus_is_for }}</h2>
            <p class="page-section__content mb-4">{{ site.t.care_campus_content }}</p>
        </div>
        <div class="features-container container">
            <div class="features">
                <div class="feature">
                    <div class="tile feature__tile">
                        <svg class="tile__icon"><use xlink:href="/assets/site.svg#families" aria-label="Consumer" /></svg>
                        <div class="tile__title">{{ site.t.families }}</div>
                        <a href="/contact/" class="tile__btn btn btn--light">{{ site.t.learn_more }}</a>
                    </div>
                </div>
                <div class="feature">
                    <div class="tile feature__tile">
                        <svg class="tile__icon"><use xlink:href="/assets/site.svg#homecare" aria-label="Restaurant" /></svg>
                        <div class="tile__title">{{ site.t.home_care }}</div>
                        <a href="/contact/" class="tile__btn btn btn--light">{{ site.t.learn_more }}</a>
                    </div>
                </div>
                <div class="feature">
                    <div class="tile feature__tile">
                        <svg class="tile__icon"><use xlink:href="/assets/site.svg#long-term-care" aria-label="Retailer" /></svg>
                        <div class="tile__title">{{ site.t.long_term_care }}</div>
                        <a href="/contact/" class="tile__btn btn btn--light">{{ site.t.learn_more }}</a>
                    </div>
                </div>
                <div class="feature">
                    <div class="tile feature__tile">
                        <svg class="tile__icon"><use xlink:href="/assets/site.svg#assisted-living" aria-label="Consumer" /></svg>
                        <div class="tile__title">{{ site.t.assisted_living }}</div>
                        <a href="/contact/" class="tile__btn btn btn--light">{{ site.t.learn_more }}</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="testimonials" class="page-section section-testimonial container">
        <div class="row">
            <div class="col pr-md-6">
                <div class="h4">{{ site.t.testimonials }}</div>
                <h2>{{ site.t.meaningful_work_has_future }}</h2>
            </div>
            <div class="testimonial col pt-md-2">
                <blockquote>"{{ site.t.testimonial }}"</blockquote>
                <div class="testimonial-bio">
                    <img src="/assets/testimonial.png" alt="{{ site.t.testimonial_author }}" />
                    <div class="testimonial-author">
                        <div class="testimonial-author__name">{{ site.t.testimonial_author }}</div>
                        <div class="testimonial-author__title h5">{{ site.t.testimonial_title }}</div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="certification" class="page-section section-certification">
        <div class="container container--wide">
            <div class="row">
                <div class="col col-img">
                    <img src="/assets/hand-phone.png" alt="Care Campus mobile app" />
                </div>
                <div class="col col-desc">
                    <h2>{{ site.t.certification }}</h2>
                    {{ site.t.certification_content }}
                </div>
            </div>
        </div>
    </section>
    {% include get-started.html %} -->
</article>
