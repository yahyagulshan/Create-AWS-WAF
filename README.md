# Creating AWS WAF Web ACL: Step-by-Step Guide
Introduction
This document provides a step-by-step guide on creating a Web Application Firewall (WAF) Web ACL using the AWS Management Console. The Web ACL will help protect your web applications from common web exploits.

## Step 1: Accessing the AWS WAF Console 
Open the AWS Management Console.
In the search bar, type "WAF" and select "WAF & Shield" from the results.
## Step 2: Navigating to AWS WAF
Within the WAF & Shield dashboard, click on "Go to AWS WAF."
![image](https://github.com/yahyagulshan/Create-AWS-WAF/assets/59036269/468cf609-48e7-4262-9662-b3dfcb92d3b2)





## Step 3: Creating a Web ACL
In the AWS WAF console, click on "Create Web ACL."
![image](https://github.com/yahyagulshan/Create-AWS-WAF/assets/59036269/ce53e090-10a4-49c3-8e9d-9fe71cdbc807)

## Step 4: Configuring Web ACL Settings
On the new page, select the appropriate AWS region.
Provide a suitable name for your Web ACL.
Click on "Next" to proceed.
![image](https://github.com/yahyagulshan/Create-AWS-WAF/assets/59036269/05e7551b-29f8-43de-994e-54cc21509a70)


## Step 5: Adding Rules to the Web ACL
Click on "Add Rules."
Choose the desired rule type from the available options.
![image](https://github.com/yahyagulshan/Create-AWS-WAF/assets/59036269/a45b7d66-30b1-4efb-8b53-e089983b2837)




a. Managed Rules:
Select either paid or free options based on your requirements.
![image](https://github.com/yahyagulshan/Create-AWS-WAF/assets/59036269/e1a28e2a-8f7a-435f-a2a7-1ac3271163ad)



With managed rules, we have both options paid and free. We can choose as per our requirements.

b. Add Your Own Rules:
Configure custom rules as needed.
![image](https://github.com/yahyagulshan/Create-AWS-WAF/assets/59036269/7464d340-6a0c-4307-a69f-cf86b741459c)

## Step 6: Setting Default Web ACL Action
After configuring rules, select the default Web ACL action for requests.
Click on "Next" to proceed.
![image](https://github.com/yahyagulshan/Create-AWS-WAF/assets/59036269/83cf9b16-8a2c-4452-a4b3-619fecf4e126)


Select default web acl action for requests 
Click on next
![image](https://github.com/yahyagulshan/Create-AWS-WAF/assets/59036269/ca8f24ed-c709-4bca-9bb3-a0d4ef3d4bf7)

## Step 7: Request Sampling Options
Choose request sampling options as needed.
Click on "Next" to proceed.
![image](https://github.com/yahyagulshan/Create-AWS-WAF/assets/59036269/e35e7538-4cd3-4fe0-95b7-4f3edcba58c2)


## Step 8: Review and Create
Review all the details provided on the page.
Ensure that the selected region, Web ACL name, rules, and actions are accurate.
Click on "Create Web ACL" to finalize the process.
![image](https://github.com/yahyagulshan/Create-AWS-WAF/assets/59036269/539ca9b9-1259-4894-b85e-c92c62c43c6d)





