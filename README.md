# S3BucketWeb



&nbsp;







Host a Website on Amazon S3





![image_alt](https://github.com/animatorsingh/S3BucketWeb/blob/ba92c092ff96ffe7850b3e6ccedc1382d98ea956/static_webiste_hosting_documentation.webp)







Introducing Today's Project!



In this project, I will demonstrate... I'm doing this project to learn s3 and how to host a website on s3 bucket





Tools and concepts

Services I used were...S3 bucket Key concepts I learnt is ACL and website hosting option in AWS S3 bucket





Project reflection

This project took me approximately 20 mins

&nbsp;



How I Set Up an S3 Bucket



Creating an S3 bucket took me less then 3 mins





The Region I picked for my S3 bucket was ap-soth-1 ... because i am from india this is the best region for me





S3 bucket names are globally unique! This means...every bucket name on aws like aws it name shoudl be unique

&nbsp;



Upload Website Files to S3



index.html and image assets

I uploaded two files to my S3 bucket - they were... index.html and all of the other files in which we have css and images





Both files are necessary for this project as...one is index.html and other files are images css

&nbsp;



Static Website Hosting on S3



Website hosting means we host our files on web server so everyone can see that





To enable website hosting with my S3 bucket, go to properties and in last option you can see static website hosting





An ACL is... access control list which kind of provide security and access control , so who can access objects in bucket and who can't

&nbsp;



Bucket Endpoints



Once static website is enabled, S3 produces a bucket endpoint URL, which is...http://hostingwebsitetestabhi.s3-website.ap-south-1.amazonaws.com





When I first visited the bucket endpoint URL, I saw... The reason for this error was...and forbidden error

&nbsp;



Success!



To resolve this 403 Forbidden error, by allow object 

&nbsp;











