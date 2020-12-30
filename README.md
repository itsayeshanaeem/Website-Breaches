# Challenge 3: Website Deployment

Welcome to Challenge 3.

This project was bootstrapped with [Create Next App](https://github.com/segmentio/create-next-app).

## Task 1 

Given this project deploy it to AWS preferable in an automated and reproducible fashion. The website should be reachable from all over the world.

* http://website-breaches.s3-website.eu-central-1.amazonaws.com/
## Task 2 -  

Adjust the solution to restrict access to the website by using mechanisms that can be adapted programmatically.

* The access can be managed by doing changes in Iac repo for s3 bucket

## Task 3  

There is one simple issue which hinders a deployment. Find and fix it. 

* The issue was with package.json file. Previosuly the .html was not being created while deployment but after adding *next export*  a static HTML file for page in the page directory was created

## Optional - Bonus

What other issues can you identify in the given site? What types of improvements would you suggest?
