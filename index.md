---
title: Welcome to myBlog
---

> *"Never say never; everything is possible!"*
> 
> Foo Yoke King, King, has about a decade of IT experience and plays multiple roles in organisations in a fast-paced environment and various sectors, from the range of project manager, product owner, consultant, process analyst, business analyst, system analyst/engineer, and developer.
> 
> Throughout King's career, King has managed and implemented the business continuity plan, disaster recovery plan, business processes reengineering, knowledge management, enterprise resource planning (ERP) application, business intelligence applications, and multiple IT systems, web-based applications, network and security projects and achieved outperforming results.

# What is it for me?
A career development plan is a roadmap that outlines an individual's goals and objectives for their professional growth and development. It typically includes a self-assessment of skills, interests, and values, as well as specific steps to achieve career goals. The plan can include short-term goals such as learning a new skill, and long-term goals such as pursuing a promotion or changing careers. It may also include strategies for networking, education, and mentoring to support the individual's career aspirations. A career development plan helps individuals take control of their professional growth and create a plan to achieve their career objectives, and can be updated and revised as needed to reflect changing goals and circumstances.

### *I have created several posts to help you plan your career development*
{% for post in site.posts %}   
### [{{ post.title }}](/{{ post.url }})
Created on **{{ post.date | date: "%e %B %Y" }}**            
{% endfor %}
