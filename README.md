# Challenge 3: Website Deployment

Welcome to Challenge 3.

This project was bootstrapped with [Create Next App](https://github.com/segmentio/create-next-app).

## Task 1 

Given this project deploy it to AWS preferable in an automated and reproducible fashion. The website should be reachable from all over the world.

* do2s2yqmx7ku5.cloudfront.net
## Task 2 -  

Adjust the solution to restrict access to the website by using mechanisms that can be adapted programmatically.

* Mentioned in documentation done using cloudfront user via Origin Access Identity. Settings can be adapted making changed via terraform in the following repo: https://github.com/itsayeshanaeem/Website-Breaches-IAC

## Task 3  

There is one simple issue which hinders a deployment. Find and fix it. 

* The issue was with package.json file. Previosuly the .html was not being created while deployment but after adding *next export*  a static HTML file for page in the page directory was created

## Optional - Bonus

What other issues can you identify in the given site? What types of improvements would you suggest?
