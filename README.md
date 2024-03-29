# Duality

This project is a submission for the HubSpot Themes Challenge 2021 Hackathon. This submission acts as a collection of landing pages and support pages for Hubspot's CMS marketplace. I developed everything except for the Three.js orb on the front page. I'm unable to give people access to the CMS funcitonality unless they follow the below steps and create a hubspot account, so please see the attached video link: https://youtu.be/YzVp0PwcNuQ

Hackathon overview: https://hubspot.devpost.com


**Link to project:** http://hubspot-developers-wz43ci-21079035.hs-sites.com/duality

See CMS functionality: https://youtu.be/YzVp0PwcNuQ

<a target="_blank" href="http://hubspot-developers-wz43ci-21079035.hs-sites.com/duality">
    <img src="https://user-images.githubusercontent.com/87950479/178039636-54504b98-4ad8-488b-bf02-1380e8e4f109.gif" width="100%" alt="CMS App"/>
</a>


## How to Launch

### To download Duality using the HubSpot CMS CLI:

Before getting started, you will need to have [Node.js](https://nodejs.org) installed, the [HubSpot CMS CLI](https://developers.hubspot.com/docs/cms/guides/getting-started-with-local-development#install-dependencies) installed.

1. Navigate to the directory that you want to use for your project
2. Run `hs create website-theme <directory>` to create the project
3. [Configure](https://developers.hubspot.com/docs/cms/guides/getting-started-with-local-development#configure-the-local-development-tools) the local development tools for the portal(s) you'd like to use for your project.
4. Run `hs watch --portal=<portal> src <directory> --initial-upload` to upload all the files in the project and [watch for changes](https://developers.hubspot.com/docs/cms/developer-reference/local-development-cms-cli#watch) to files in the `src` directory

Please reference the _[Quick start guide to developing on the HubSpot CMS](https://developers.hubspot.com/docs/cms/guides/getting-started)_ and _[Getting started with local development](https://designers.hubspot.com/tutorials/getting-started-with-local-development)_ articles for more information.


## How It's Made:

**Tech used:** Hubl (HubSpots templating language), HTML, CSS, JavaScript, jQuery, and Three.js

Duality's drag and drop/customization functionality comes from Hubl, which also controls the spacing and layout of each page. The 3D orb on the fron page was created with Three.js, and any functionality (the mobile navigation bar and the map) were created using jQuery and JavaScript. 

## Lessons Learned:

This contest taught me how to be comfortable diving into a new technology. There aren't too many outside resources on Hubl or HubSpots environment, so I really had to disect the documentation. As a result I've become more confident in relying on Documentation and using the DOM to style my web pages. Overall it was a great expereince that accelerated my coding skills. I certainly plan on competing in another hackathon in the future!


