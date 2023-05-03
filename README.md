### Hi there 👋

I'm a **software developer** 👨‍💻 with a **design background** 👨‍🎨 who can build a website from the ground up 🏗️ and make it look fantastic 💅. In addition to a wealth of technical skills, I also pride myself on being a **strong communicator** who can break down complex topics without judgment or jargon. 

I spent the last 5 years as a developer, **technical project manager**, and technology department head at an e-commerce company that took in $60M per year in revenue. I'm looking for my next opportunity so here are some of my best work examples:

------

### [TeeTurtle.com Homepage & Interface](https://www.teeturtle.com/)
***HTML, CSS, JavaScript, JQuery, Bootstrap, Design, Project Management***

At the time, TeeTurtle's entire $10M e-commerce business was hosted on a bog-standard $200 per month Shopify Premium plan. It was sluggish, outdated, and exceedingly restrictive to the business's growth. With the help of a 3rd party project manager and backend developer we duplicated all necessary functionality on our own custom PHP platform, all within eight months. This allowed us to tailor the platform to the specific needs of the business. I was responsible for spec gathering, developer write-ups, stakeholder management, and, most of all, frontend design and development of the entire look and feel of the new site. By 2021, we crossed more than $20M in e-commerce sales, in part due to the speed and efficiency of the new platform that allowed us to easily accommodate the massive increase in online sales during the early months of the pandemic.

The current TeeTurtle.com is still using the same design and interface which I created in 2019 (with some cosmetic updates in 2021, also coded by me). 🔗 [Take a look here!](https://www.teeturtle.com/)

------

### [Personal Coaching Website and Marketing Platform](https://alexandriathibodeaux.com)
***Python, HTML, Sass, CSS, JavaScript, SQL, Django, Wagtail, Bootstrap, AWS ElasticBeanstalk, EC2, RDS, S3, ELB***

A coaching professional needed a platform to tell people about themselves, market their offerings, take payments, provide access to content behind a paywall and blog. I created this Django app using Wagtail CMS so that all of this could be done in one place. The app integrates with MailChimp Marketing and PayPal APIs to automate list building and taking payments. Everything on the site is configurable by the end user without any need for code. Clients can create accounts, pay and access exclusive content that free users cannot access. Initially hosted on Heroku, I switched hosting to AWS with only minutes of downtime.

Please checkout out the [live site here](https://alexandriathibodeaux.com) and the [source code here](https://github.com/jpmalley/at-public).

------

### [File Transfer App](https://filetransfer.johnpmalley.com)
***Python, HTML, Sass, CSS, JavaScript, SQL, Django, Bootstrap, AWS ElasticBeanstalk, EC2, RDS, S3, ELB***

This simple Django app uploads a file securely to Amazon S3 and generates an easily sharable presigned URL with user specified expiration. Upon clicking upload, an AJAX request is sent to the server to generate presigned post URL with specific conditions to the file being uploaded. The request returns a post URL and the client's browser then handles the upload directly to S3 via JavaScript, avoiding additional server-side load. After a successful upload, the server generates a presigned download URL that expires at the specified time. Object lifecycles in the S3 bucket are managed to ensure objects are deleted permanently within 24 hours of link expiration. HTTP/1.1 Caching is also managed to ensure expiration coincides with link expiration.

Completed in March 2023, you can checkout [source code here](https://github.com/jpmalley/filetransferapp) and the [live demo here](https://filetransfer.johnpmalley.com).

------

### [Unstable Games Landing Pages](https://www.teeturtle.com/site/here-to-slay)
***HTML, CSS, Custom JavaScript Animations (GSAP), Bootstrap, Design***

TeeTurtle needed a striking landing page design for all of their major releases under the Unstable Games brand. These pages would serve multiple purposes throughout a title's development. Some of those functions included:

- Teaser page before Kickstarters
- Definitive source of product information during Kickstarters
- Preorder page and source of updates on shipping timelines
- And finally, a static sales page that introduces people to the game who have never seen it before

I was given a blank canvas and decided to delve into javascript animations using the GSAP framework. With the help of the art team, we were able to convert already-produced animation assets to scroll-triggered web animations. It was easy to create a workflow into the product development cycle that made creating these animations took only a few minutes for each title.

The page for Here to Slay is one of the best and still is live on the Unstable Games website. 🔗 [Take a look here!](https://www.teeturtle.com/site/here-to-slay)
