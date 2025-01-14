---
layout: default
title: Index
---

# Index Page

Welcome to the index of all pages.

## Pages
{% for page in site.pages %}
- [{{ page.title }}]({{ page.url | relative_url }})
{% endfor %}


<div class="container">
    <h1>Subjects</h1>
    <div class="subjects">
        <div class="subject-card">
            <img src="image1.jpg" alt="Synology NAS help with use">
            <h2>Help with use</h2>
            <ul>
                <li><a href="#">How do you transfer drives from your old Synology NAS?</a></li>
                <li><a href="#">How do you make your Synology NAS externally accessible?</a></li>
                <li><a href="#">Advice on streaming media with your NAS</a></li>
                <li><a href="#">How do you create a shared folder on your Synology?</a></li>
                <li><a href="#">How do you transfer data to your Synology NAS from Windows?</a></li>
            </ul>
        </div>
        <div class="subject-card">
            <img src="image2.jpg" alt="Synology NAS help with installation">
            <h2>Help with installation</h2>
            <ul>
                <li><a href="#">How do you install your Synology NAS?</a></li>
                <li><a href="#">How do you install Plex on your Synology NAS?</a></li>
                <li><a href="#">How do you set up Synology Drive Server?</a></li>
                <li><a href="#">How do you make IP camera recordings with your Synology NAS?</a></li>
            </ul>
        </div>
        <div class="subject-card">
            <img src="image3.jpg" alt="Synology NAS help with problems">
            <h2>Help with problems</h2>
            <ul>
                <li><a href="#">How do you reset your Synology NAS?</a></li>
                <li><a href="#">How do I change the RAID setup on my Synology NAS?</a></li>
                <li><a href="#">How do you transfer files from macOS to your Synology NAS?</a></li>
            </ul>
        </div>
    </div>
</div>