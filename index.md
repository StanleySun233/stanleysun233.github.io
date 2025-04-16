---
layout: default
title: Home
---

<style>
.school-header {
    display: flex;
    align-items: center;
    margin-bottom: 10px;
}

.school-logo {
    width: 50px;
    height: 50px;
    margin-right: 15px;
    object-fit: contain;
}

.school-info {
    flex: 1;
}

.school-info h3 {
    margin: 0;
}

.school-info p {
    margin: 5px 0 0 0;
}
</style>

{% include profile.html %}

## Education

{% include education.html %}

## Research Papers

{% include papers.html %}

## Work Experience

{% include experiences.html %}

## Projects

{% include projects.html %} 