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

<div id="nasbox">
    <h1>Help with your product</h1>
    <div class="product-info">
        <img src="nas-image.jpg" alt="Synology DS923+">
        <div class="details">
            <strong>Synology DS923+</strong><br>
            <span>Number of hard drive slots: 4</span><br>
            <span>Suitable for hard drive size: 3.5-inch HDD, M.2 NVMe</span><br>
            <span>Internal RAM: 4 GB</span><br>
            <a href="#">40 reviews</a>
        </div>
    </div>
    <div class="tips">
        <h2>Read all tips here</h2>
        <div class="tip-card">
            <div>
                <img src="image-49.png" alt="How do you transfer drives from your old Synology NAS?">
                <a href="/nas/What-is-NAS.html">What is a NAS and Why Use a NAS?</a>
            </div>
            <div>
                <img src="image-49.png" alt="How do you install your Synology NAS?">
                <a href="/nas/NAS-CloudStorage.html">NAS vs. Cloud Storage</a>
            </div>
            <div>
                <img src="image-49.png" alt="How do you install your Synology NAS?">
                <a href="/nas/ChoosingtheRightNASforYourNeeds.html">Choosing the Right NAS for Your Needs</a>
            </div>
        </div>
    </div>
    <div class="subjects">
        <div class="subject-card">
            <img src="image-47.png" alt="Help with use">
            <h3>Help with use</h3>
            <ul>
                <li><a href="/nas/HowtoTransferHardDrivesBetweenSynologyNASDevices.html">How to Transfer Hard Drives Between Synology NAS Devices</a></li>
                <li><a href="/nas/AccessingYourSynologyNASExternallyviaQuickConnect.html">Accessing Your Synology NAS Externally via QuickConnect</a></li>
                <li><a href="/nas/StreamingMediawithYourNAS.html">Streaming Media with Your NAS</a></li>
            </ul>
        </div>
        <div class="subject-card">
            <img src="image-48.png" alt="Help with installation">
            <h3>Help with installation</h3>
            <ul>
                <li><a href="/nas/HowtoInstallYourSynologyNAS.html">How to Install Your Synology NAS</a></li>
                <li><a href="/nas/InstallingPlexonYourSynologyNAS.html">Installing Plex on Your Synology NAS</a></li>
                <li><a href="/nas/SettingUpSynologyDriveServer.html">Setting Up Synology Drive Server</a></li>
                <li><a href="/nas/RecordingIPCameraFootagewithYourSynologyNAS.html">Recording IP Camera Footage with Your Synology NAS</a></li>
            </ul>
        </div>
        <div class="subject-card">
            <img src="image-49.png" alt="Help with problems">
            <h3>Help with problems</h3>
            <ul>
                <li><a href="/nas/How-to-reset-your-Synology-NAS.html">How to Reset Your Synology NAS</a></li>
                <li><a href="/nas/AdjustingtheRAIDSetuponYourSynologyNAS.html">Adjusting the RAID Setup on Your Synology NAS</a></li>
            </ul>
        </div>
    </div>
</div>