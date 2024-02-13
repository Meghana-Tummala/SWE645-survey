#The links can be accessed here!!!
https://s3.amazonaws.com/meghana.tummala/index.html
http://ec2-54-175-148-216.compute-1.amazonaws.com/
# SWE645-survey
# My Journey with AWS: Deploying Web Applications

Welcome to my little corner of the web where I share my adventures in tech. Today, I'm excited to walk you through my experience deploying web applications using Amazon Web Services (AWS). 

## Part 1: Hosting Static Sites with S3

### Creating My First Bucket

My first task was to create a bucket in S3. The AWS Management Console made this process pretty straightforward. I came up with a unique name for my bucket (which took a few tries, to be honest) and chose a region. I had to remember to uncheck the "Block all public access" option to make my site accessible to the world, which felt a bit scary, but also exciting.

### Enabling Static Website Hosting

Next, I ventured into my bucket's settings to turn on static website hosting. AWS asked for an index document and an error document, which I had ready as `index.html` and `error.html`.

### Uploading My Website

The next step felt like moving into a new home. I uploaded all my HTML, CSS, and JavaScript files to the bucket. Setting the files to be publicly readable was crucial—I wanted the world to see my work, after all!

### Crafting the Perfect Bucket Policy

The final touch was adding a bucket policy. This bit of JSON magic was what allowed everyone to view my files. I carefully replaced `your-bucket-name` in the example policy with my actual bucket name, and my static site was live!

## Part 2: Bringing Dynamics with EC2

### Launching an Instance

I selected an Amazon Machine Image (AMI), chose an instance type, and configured the details. AWS guides you through adding storage, tagging, and finally, setting up a security group. I made sure to allow HTTP, HTTPS, and SSH access—my site needed to be secure but accessible.

### Connecting to My Instance

Connecting to my EC2 instance for the first time was thrilling. I chose SSH for that hands-on feeling. Following AWS's guidance, I used my terminal to establish a connection. It was like unlocking a door to a new world where I could set up my dynamic application.

### Deploying the Application

With access to my instance, I installed a web server and the necessary programming languages. Uploading my application code felt like planting a flag on uncharted territory. My dynamic site was starting to take shape.

### Opting for a Static IP

I learned that EC2 instances use dynamic IP addresses, which change upon restarts. To keep things consistent, I allocated an Elastic IP address and associated it with my instance. It was like getting a permanent address in the vast world of the internet.

## Reflections

And that's the story of how I deployed my web application using AWS. The journey taught me the ins and outs of web hosting and gave me a deep appreciation for cloud services. If you're diving into AWS, I hope my experience lights the way and inspires you to explore, learn, and create. Here's to many more adventures in the cloud!
