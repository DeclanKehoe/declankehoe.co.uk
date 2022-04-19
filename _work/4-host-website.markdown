---
layout: page
title: 'HOST - Humanising Online Services Toolkit'
description: 'For Imago Software. I was BA on a small, agile team. We were collaborating with charities to develop a toolkit so charity services could go online, and delivered a full stack framework to facilitate that. My job was to help bridge the developers and the clients.'
banner:
    src: '../../images/imago-site-screenshot.png'
    alt: 'A screenshot of my generative music app'
    caption: 'A screenshot of the code and the site side-by-side'
---

You can [see the framework](https://humanizing-online-services-toolkit.netlify.app/toolkit) for the toolkit we made, unfortunately the clients have not yet updated it with their own content, but the software works!

![Screenshot of the Imago software project](/assets/images/imago-site-screenshot.png)

### Goals & Overview

The aim of this website is to present a toolkit to charities & organisations which provide educational services to refugees, which helps them to keep the sense of 'human touch' in their work, even when online.

Everything in the site itself has been built and designed completely from scratch by the team, following an **agile** approach to development. We have set ourselves ambitious deadlines to ensure that the clients have useful software to test and give feedback on as quickly as possible.

### Technology

By following the agile approach, we decided to build out only the most vital components as we went. This meant that to start with we just built the frontend and hardcoded everything that was seen. For this stage we used **react** and **typescript** as the frameworks, deployed to **netlify**, and used **yarn** as the package manager.

We also built a bespoke back-end solution for the researchers such that they can continue adding their research to the site in an easy way, while still benefiting from the design of the front end we developed. In the end a **PostgreSQL** database with a **Django** interface was built, and content could be added through a web GUI and would then be automatically formatted and published on the site.

### Collaborative Development

This project's biggest challenge was in attempting to build for client's who were unsure as to what precisely they were looking for. us to make This process has lead to a lot of  **prototyping**, regular **presentations** of progress, and **iterations** based on feedback from the researchers, who are producing the information that will eventually (hopefully) be on the website.