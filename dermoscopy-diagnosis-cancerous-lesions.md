---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

id: skin-cancer-detection
layout: default
title: >
    Dermoscopy diagnosis of cancerous lesions utilizing dual deep learning algorithms via visual and audio (sonification) outputs: Laboratory and prospective observational studies
description: 
date: 2019-01-20
slug: dermoscopy-diagnosis-cancerous-lesions
---
<div class="page-publication">
<div class="page-header">
    <div class="page-header__content container">
        <a href="/publications" class="h5 page-label">Back to Publications</a>
        <h1 class="h2 page-title">Dermoscopy diagnosis of cancerous lesions utilizing dual deep learning algorithms via visual and audio (sonification) outputs: Laboratory and prospective observational studies</h1>
        <div class="publication-header__footer">
            <p class="publication-date">Published: {{ page.date | date: "%B %d, %Y" }}</p>
            <a class="publication-download" href="/assets/PIIS2352396419300337.PDF" target="_blank"><svg class="icon" aria-title="download PDF"><use xlink:href="/assets/site.svg#pdf-download" /></svg> Download PDF</a>
        </div>
    </div>
</div>
<article class="page-content container"> 
    <div class="page-section">    
        <h2>Abstract:</h2>
        <h3 class="h4">Background</h3>
        <p>Early diagnosis of skin cancer lesions by dermoscopy, the gold standard in dermatological imaging, calls for a diagnostic upscale. The aim of the study was to improve the accuracy of dermoscopic skin cancer diagnosis through use of novel deep learning (DL) algorithms. An additional sonification-derived diagnostic layer was added to the visual classification to increase sensitivity.</p>
        <h3 class="h4">Methods</h3>
        <p>Two parallel studies were conducted: a laboratory retrospective study (LABS, <em>n</em> = 482 biopsies) and a non-interventional prospective observational study (OBS, <em>n</em> = 63 biopsies). A training data set of biopsy-verified reports, normal and cancerous skin lesions (<em>n</em> = 3954), were used to develop a DL classifier exploring visual features (System A). The outputs of the classifier were sonified, i.e. data conversion into sound (System B). Derived sound files were analyzed by a second machine learning classifier, either as raw audio (LABS, OBS) or following conversion into spectrograms (LABS) and by image analysis and human heuristics (OBS). The OBS criteria outcomes were System A specificity and System B sensitivity as raw sounds, spectrogram areas or heuristics.</p>
        <h3 class="h4">Findings</h3>
        <p>LABS employed dermoscopies, half benign half malignant, and compared the accuracy of Systems A and B. System A algorithm resulted in a ROC AUC of 0.976 (95% CI, 0.965–0.987). Secondary machine learning analysis of raw sound, FFT and Spectrogram ROC curves resulted in AUC's of 0.931 (95% CI 0.881–0.981), 0.90 (95% CI 0.838–0.963) and 0.988 (CI 95% 0.973–1.001), respectively. OBS analysis of raw sound dermoscopies by the secondary machine learning resulted in a ROC AUC of 0.819 (95% CI, 0.7956 to 0.8406). OBS image analysis of AUC for spectrograms displayed a ROC AUC of 0.808 (CI 95% 0.6945 To 0.9208). By applying a heuristic analysis of Systems A and B a sensitivity of 86% and specificity of 91% were derived in the clinical study.</p>
        <h3 class="h4">Interpretation</h3>
        <p>Adding a second stage of processing, which includes a deep learning algorithm of sonification and heuristic inspection with machine learning, significantly improves diagnostic accuracy. A combined two-stage system is expected to assist clinical decisions and de-escalate the current trend of over-diagnosis of skin cancer lesions as pathological.</p>
        <h3 class="h4">Citation:</h3>
        <p>The Lancet, EBioMEdicine; February 2019, Volume 40, Pages 176–183</p>
        <h3 class="h4">Link:</h3>
        <a href="https://www.thelancet.com/journals/ebiom/article/PIIS2352-3964(19)30033-7/fulltext">https://www.thelancet.com/journals/ebiom/article/PIIS2352-3964(19)30033-7/fulltext</a>
    </div>
</article>
</div>
