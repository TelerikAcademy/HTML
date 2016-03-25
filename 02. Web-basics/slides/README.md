<!-- section start -->
<!-- attr: { id:'', class:'slide-title', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# Web Technologies Basics
## Concepts

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic00.png" style="top:52.42%; left:57.08%; width:45.84%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic01.png" style="top:39.67%; left:7.73%; width:18.93%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic02.png" style="top:5.29%; left:88.84%; width:15.91%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic03.png" style="top:2.99%; left:53.75%; width:23.41%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic04.png" style="top:9.74%; left:9.40%; width:33.57%; z-index:-1" /> -->
<div class="signature">
	<p class="signature-course"></p>
	<p class="signature-initiative"></p>
	<a href="" class="signature-link"></a>
</div>




<!-- section start -->
<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# Table of Contents
- Web Sites and Web Applications
- Web 1.0, 2.0, 3.0
- Web Browsers
- Hardware Servers
- Web Servers
- Client-Server Architecture
- 3-Tier / Multi-Tier Architectures
- Service-Oriented Architecture (SOA)

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic05.png" style="top:14.48%; left:52.66%; width:49.59%; z-index:-1" /> -->




<!-- section start -->
<!-- attr: { id:'', class:'slide-section', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# Web Sites and Web Applications
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic06.png" style="top:34.13%; left:25.51%; width:56.40%; z-index:-1" /> -->


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'' } -->
# Web Page
- **Document** or information resource that is suitable for the World Wide Web
- Can be accessed through a web browser and displayed on a monitor or mobile device
- This information is usually in HTML or XHTML format, and may provide navigation to other web pages via hypertext links
- Web pages frequently refer to other resources such as style sheets (CSS), scripts (JavaScript) and images into their final presentation


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'' } -->
# Web Site
- **Collection****of related web pages**containing web resources (web pages, images, videos, CSS files, JS files or other digital assets)
- Common navigation between web pages
- A website is hosted on at least one web server
- Accessible via a network (such as the Internet)
- All publicly accessible websites collectively constitute the World Wide Web


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# Web Application
- Next level web sites
- High interactivity
- High accessibility (Cloud)
- AJAX, Silverlight, Flash, Flex, etc.
- Applications are usually broken into logical chunks called "tiers", where every tier is assigned a role
- Desktop-like application in the web browser
- Web applications on desktop (Windows 8)

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic07.png" style="top:13.00%; left:88.30%; width:15.87%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic08.png" style="top:15.98%; left:64.56%; width:17.63%; z-index:-1" /> -->




<!-- section start -->
<!-- attr: { id:'', class:'slide-section', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# Web Browsers andLayout Engines
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic09.png" style="top:49.48%; left:55.46%; width:12.61%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic10.png" style="top:49.48%; left:13.10%; width:13.35%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic11.png" style="top:49.48%; left:41.19%; width:12.61%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic12.png" style="top:49.37%; left:83.95%; width:15.03%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic13.png" style="top:49.48%; left:28.20%; width:11.34%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic14.png" style="top:49.48%; left:69.72%; width:12.61%; z-index:-1" /> -->


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'' } -->
# Web Browsers
- Program designed to enable users to access, **retrieve and view documents**and other resources from the Web
- Main responsibilities:
  - Bring information resources to the user (issuing requests to the web server and handling any results generated by the request)
  - Presenting web content (render HTML, CSS, JS)
  - Capable of executing applications within the same context as the document on view (Flash)


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'' } -->
# Layout Engines
- Software component that **displays the formatted content** on the screen combining:
  - Marked up content (such as HTML, XML, image files, etc.)
  - Formatting information (such as CSS, XSL, etc.)
- It "paints" on the content area of a window, which is displayed on a monitor or a printer
- Typically embedded in web browsers, e-mail clients, on-line help systems or other applications that require the displaying (and editing) of web content
- How Browsers Work


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# Layout Enginesand Web Browsers
- Trident-based
  - Internet Explorer, Netscape, Maxthon, etc.
- Gecko-based
  - Firefox, Netscape, SeaMonkey, etc.
- Blink-based
  - Chrome, Opera
- WebKit-based
  - Safari, iOS, Maxthon, Chrome (up to v27), etc.
- EdgeHTML (fork of Trident)
  - Spartan (the new IE)
  - Windows 10 and Windows 10 (Mobile)

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic15.png" style="top:60.14%; left:98.59%; width:7.54%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic16.png" style="top:62.58%; left:68.31%; width:6.38%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic17.png" style="top:23.95%; left:83.38%; width:7.29%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic18.png" style="top:17.16%; left:98.05%; width:8.05%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic19.png" style="top:61.76%; left:82.00%; width:11.61%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic20.png" style="top:33.92%; left:41.60%; width:63.08%; z-index:-1" /> -->


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'' } -->
# User Agent Strings
- Identify web browsers and their version
  - History of (in)compatibility attempts [link]
- Can have some additional information like layout engine, user's operating system, etc.
  - **Mozilla/5.0** – a generic term which most modern browsers use (originally indicated Netscape)
  - **Windows NT****6.3** – Windows 8.1
  - **WOW64** – Windows-On-Windows 64-bit
  - **AppleWebKit****/537.36** – Blink is a fork of WebKit
    - KHTML is the previous name of WebKit
  - **Chrome/41.0.2272.118** – real browser version
  - **Safari/537.36** – artifact against scripts sniffing

```cs
Mozilla/5.0 (Windows NT 6.3; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2272.118 Safari/537.36
```





<!-- section start -->
<!-- attr: { id:'', class:'slide-section', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# Hardware Servers
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic21.png" style="top:26.47%; left:21.05%; width:66.12%; z-index:-1" /> -->


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# Hardware Servers
- **Physical****computer**(a hardware system) dedicated to running one or more such services
- Servers are placed in collocation centers
  - Colocation facilities provide space, power, cooling, and physical security for the server
- The server may be:
  - Database server
  - File server
  - Mail server
  - Print server
  - VPS servers

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic22.png" style="top:41.42%; left:61.80%; width:32.51%; z-index:-1" /> -->




<!-- section start -->
<!-- attr: { id:'', class:'slide-section', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# Web Servers
## Apache, IIS, nginx, lighttpd, etc.

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic23.png" style="top:43.20%; left:11.23%; width:22.04%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic24.png" style="top:46.45%; left:80.47%; width:20.61%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic25.png" style="top:32.25%; left:38.36%; width:35.26%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic26.png" style="top:48.27%; left:42.51%; width:27.44%; z-index:-1" /> -->


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'' } -->
# What Do the Web Servers Do?
- All physical servers have hardware
- The hardware is controlled by the operating system
- **Web servers**are software products that use the operating  system to **handle web requests**
  - Web servers **serve****Web content**
- These requests are redirected to other software products (ASP.NET, PHP, etc.), depending on the web server settings


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# Web Servers Market Share March 2015
- Market share of the top million busiest sites
  - Apache
    - 49.35%  (493,463)
  - nginx
    - 21.22% (212,151)
  - IIS (by Microsoft)
    - 12.21% (122,069)
  - GWS (by Google)
    - 2.44% (24,434)
- Source

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic27.png" style="top:23.42%; left:59.28%; width:44.99%; z-index:-1" /> -->




<!-- section start -->
<!-- attr: { id:'', class:'slide-section', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# Client-Server Architecture
## The Classical Client-Server Model

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic28.png" style="top:12.34%; left:30.88%; width:47.60%; z-index:-1" /> -->


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'' } -->
# Client-Server Architecture
- The client-server model consists of:
  - **Server** – a single machine or cluster of machines that provides web applications (or services) to multiple clients
    - _Examples_:
      - Web server running PHP scripts or ASP.NET pages
      - IIS based Web server
      - WCF based service
      - Services in the cloud


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# Client-Server Architecture
- The client-server model consists of:
  - **Clients**–software applications that provide UI (front-end) to access the services at the server
    - _Examples_:
      - Web browsers
      - WPF applications
      - HTML5 applications
      - Silverlight applications
      - ASP.NET consuming services

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic29.png" style="top:36.14%; left:68.30%; width:28.21%; z-index:-1" /> -->


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# The Client-Server Model

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic30.png" style="top:34.38%; left:66.43%; width:16.75%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic31.png" style="top:14.99%; left:66.43%; width:16.75%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic32.png" style="top:52.89%; left:66.43%; width:16.75%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic33.png" style="top:29.70%; left:10.69%; width:21.87%; z-index:-1" /> -->


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'' } -->
# Client-Server Model – _Examples_
- Web server (Apache, IIS) – Web browser
- FTP server (ftpd) – FTP client (FileZilla)
- EMail server (qmail) – email client (Outlook)
- SQL Server – SQL Server Management Studio
- BitTorrent Tracker – Torrent client (μTorrent)
- DNS server (bind) – DNS client (resolver)
- DHCP server (wireless router firmware) – DHCP client (mobile phone /Android DHCP client/)
- SMB server (Windows) – SMB client (Windows)




<!-- section start -->
<!-- attr: { id:'', class:'slide-section', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# 3-Tier / Multi-Tier Architectures
## Classical Layered Structure of Software Systems

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic34.png" style="top:43.02%; left:21.05%; width:66.56%; z-index:-1" /> -->


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'' } -->
# The 3-Tier Architecture
- The **3-tier architecture**consists of the following tiers (layers):
  - **Front-end** (client layer)
    - Client software – provides the UI of the system
  - **Middle tier**(business layer)
    - Server software – provides the core system logic
    - Implements the business processes / services
  - **Back-end** (data layer)
    - Manages the data of the system (database / cloud)


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# The 3-Tier Architecture Model

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic35.png" style="top:37.02%; left:73.88%; width:16.75%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic36.png" style="top:18.51%; left:73.88%; width:16.75%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic37.png" style="top:53.77%; left:73.88%; width:16.75%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic38.png" style="top:29.97%; left:30.88%; width:21.87%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic39.png" style="top:29.97%; left:4.29%; width:21.23%; z-index:-1" /> -->


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# Typical Layers of the Middle Tier
- The middle tier usually has parts related to the front-end, business logic and back-end:

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic40.png" style="top:69.65%; left:48.65%; width:14.10%; z-index:-1" /> -->




<!-- section start -->
<!-- attr: { id:'', class:'slide-section', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
<!-- # Service-Oriented Architecture (SOA) -->

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic41.png" style="top:13.83%; left:32.75%; width:44.11%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic42.png" style="top:17.06%; left:8.39%; width:25.11%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic43.png" style="top:16.84%; left:77.04%; width:25.03%; z-index:-1" /> -->


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'' } -->
# What is a Service?
- In the real world a "**service**" is:
  - A piece of work performed by a service provider
  - Provides the client (consumer) some desired result by some input parameters
    - The requirements and the result are known
  - Easy to use
  - Always available
  - Has quality characteristics (price, execution time, constraints, etc.)




<!-- section start -->
<!-- attr: { id:'', class:'slide-section', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# What is "Cloud"?

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic44.png" style="top:3.23%; left:63.62%; width:39.82%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic45.png" style="top:3.23%; left:50.84%; width:33.13%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic46.png" style="top:3.53%; left:26.20%; width:36.14%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic47.png" style="top:21.16%; left:21.52%; width:21.16%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic48.png" style="top:21.16%; left:56.70%; width:24.15%; z-index:-1" /> -->


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'' } -->
# What is Cloud?
- **Cloud** ≈ multiple hardware machines combine their computing power and resources
  - Share them between multiple applications
  - To save costs and use resources more efficiently
- **Public clouds**
  - Provide computing resources on demand
    - Publicly in Internet
    - Paid or free of charge (to some limit)
  - Amazon AWS, Google App Engine, Microsoft Azure, Rackspace, PHPFog, Heroku, AppHarbor


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'' } -->
# Cloud Computing Models
- **Infrastructure as a Service (IaaS)**
  - Virtual machines in the cloud on demand
  - Users install the OS and software they need
- **Platform as a Service (PaaS)**
  - Platform, services and APIs for developers
  - E.g. Java + JBoss + JSF + JPA + MongoDB or JavaScript + Node.js + MongoDB + RabbitMQ
- **Software as a Service (SaaS)**
  - Hosted application on demand (e.g. WordPress)


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'False', style:'' } -->
# Web Technologies Basics
- Questions?


<!-- attr: { id:'', class:'', showInPresentation:'True', hasScriptWrapper:'True', style:'' } -->
# Free Trainings @ Telerik Academy
- "Web Design with HTML5, CSS3 and JavaScript" course @ Telerik Academy
    - html5course.telerik.com
  - Telerik Software Academy
    - academy.telerik.com
  - Telerik Academy @ Facebook
    - facebook.com/TelerikAcademy
  - Telerik Software Academy Forums
    - forums.academy.telerik.com

<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic49.png" style="top:58.18%; left:90.52%; width:16.97%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic50.png" style="top:34.35%; left:68.14%; width:36.30%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic51.png" style="top:48.92%; left:75.91%; width:10.85%; z-index:-1" /> -->
<!-- <img class="slide-image" showInPresentation="true" src="\imgs\pic52.png" style="top:11.88%; left:90.52%; width:15.21%; z-index:-1" /> -->
