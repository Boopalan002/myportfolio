---
title: "JAMStack"
date: 2022-03-01T12:14:34+06:00
image: "images/portfolio/jamstack.jpeg"
tags: ["Web Architecture"]
description: "JAM Stack"
draft: false
---

# *What is JAMStack?*

- "Jamstack" was originally cased as "JAMstack" where "JAM" stood for JavaScript, API & Markup.
- ”A modern web development architecture based on client-side JavaScript, reusable APIs, and prebuilt Markup“ - *Mathias Biilmann (CEO & Co-founder of Netlify)*

#### JavaScript

Dynamic functionalities are handled by JavaScript. There is no restriction on which framework or library you must use.

#### APIs

Server side operations are abstracted into reusable APIs and accessed over HTTPS with JavaScript. These can be third party services or your custom function.

#### Markup

Websites are served as static HTML files. These can be generated from source files, such as Markdown, using a Static Site Generator.

Today, Jamstack is used to more broadly refer to an architectural approach for building websites. Though there are varying opinions on what exactly Jamstack means today, these attributes are present in most sites that claim to be Jamstack sites:

1. ***Decoupled*** - The front end uses tooling separate from the back end. The front end is typically built using a static site generator. And the back end is often integrated with the front through the use of APIs used during the build process. Server-side processes can also be run using serverless functions.
2. ***Static-first*** - While various practices exist for introducing dynamic elements to Jamstack sites, most are pre-rendered, which means the front end was built and compiled into HTML, CSS, and JavaScript files.
3. ***Progressively enhanced*** - JavaScript can be introduced to pre-rendered sites on an as-needed basis, thus increasing performance in the browser.

# *Benefits*

1. ***Faster performance*** - Serve pre-built markup and assets over a CDN.
2. ***More secure*** - No need to worry about server or database vulnerabilities.
3. ***Less expensive*** - Hosting of static files is cheap or even free.
4. ***Better developer experience*** - Front end developers can focus on the front end, without being tied to a monolithic architecture. This usually means quicker and more focused development.
5. ***Scalability*** - If your product suddenly goes viral and has many active users, the CDN seamlessly compensates.

# *Best Practices*

* The following tips will help you leverage the best out of the stack.
    1. ***Content delivery network*** - Since all the markup and assets are pre-built, they can be served via CDN. This provides better performance and easier scalability.
    2. ***Atomic deploys*** - Each deploy is a full snapshot of the site. This helps guarantee a consistent version of the site globally.
    3. ***Cache invalidation*** - Once your build is uploaded, the CDN invalidates its cache. This means that your new build is live in an instant.
    4. ***Everything in version control*** - Your codebase lives in version control system, such as Git. The main benefits are changing the history of every file, collaborators and traceability.
    5. ***Automated builds*** - Your server is notified when a new build is required, typically via webhooks. Server builds the project, updates the CDNs and the site is live.

# *Work Flow*

<img src="/images/portfolio/workflow.png" width="100%" height="auto"/>

# *Coupled*

COUPLED is when the content of a website is created, managed, and stored on the site’s back end, where the database lies (such as the WordPress admin). This content is then pulled from the back end and represented in the browser through a front-end interface (such as a WordPress template). In a way, a “coupled” application is the traditional “full-stack” with the back-end and front-end being different sides of the same app.

# *Decoupled*

In contrast, DECOUPLED is when the back end and the front end are managed separately — meaning that the database and management tools will be on one server, and the front-end somewhere else. Naturally, there needs to be a medium by which both are connected, which is normally an API. What’s more, since the back-end now is effectively separated from the front end, there could be, in fact, several front ends in different locations! (Think of different storefronts using the same engine, such as Shopify.)

# *Headless*

In a nutshell, HEADLESS software simply doesn’t have a front-end or a presentation layer. A headless CMS, for example, is one that could generate static content and push it anywhere: a mobile app, an Internet of Things device, a static website. Admittedly, this is also a “decoupled” situation, but here you might not even need an API. Think of a WordPress engine that exported its posts to be served as static HTML files: that’s headless. 

# *Getting Started JAMstack*

#### Development

* However you decide to generate your HTML assets is up to you. The three most common approaches are:
    1. ***Hand coding*** - Simple and effective method of writing HTML, it's ideal for super simple pages.
    2. ***Static Site Generators*** - Most Jamstack sites are powered by a static site generator. There's no enforcement on which SSG you decide to use (Next.js, Gatsby, Hugo).
    3. ***Site Builders*** - Tools that bring Jamstack to less technical users, while enabling developers to customize sites through modern tooling (Stackbit, Builder.io, CloudCannon).

#### Deployment

Your built site needs to be hosted somewhere. There are great services that provide this for free and with ease.

- Netlify
- Vercel
- Github Pages
- Digital Ocean
- Azure Static Web Apps

#### Dynamic Parts

* Jamstack websites don't have to be static. There are great services available to help bring some dynamic data to your product.
    - ***Custom functions***
        You can also abstract your own functions into reusable APIs.
            1. AWS lambda functions
            2. Netlify functions
    - ***Custom data***
        As you add features to your site, you may want to store user profiles, shopping cart data, game levels, or other dynamic data. There are many DBaaS (database as a service) tools out there today.
            
            1. Fauna
            2. Hasura
            3. MongoDB Atlas & AWS DynamoDB
   - ***Comments***
        Many Jamstack products have dynamic comment sections. These are typically used on blogs.

            1. Staticman
            2. Disqus
    - ***Forms***
        A great way to interact with your audience. Tools like Netlify support this by default, though there are other form-based services.

            1. Netlify Forms
            2. Getform
            3. FormKeep

#### CMS

Jamstack sites can also be controlled via a Content Management System, these are typically known as Headless CMS. Once a change in the CMS is made, a new build of your site will be triggered and then deployed as static assets.

1. Netlify CMS
2. Contentful
3. Ghost
4. Strapi
5. Forestry
6. Sanity.io
7. GraphCMS





