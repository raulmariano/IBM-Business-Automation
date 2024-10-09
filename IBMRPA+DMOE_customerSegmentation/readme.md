# How to consume IBM BAMOE decision microservices by IBM RPA bots?

After the last posts and getting feedback from community members, I felt the need to post new technical content, but with a slightly different approach than the previous ones. I prepared content that technically shows the integration of technologies on a study case – despite being a fictitious case, I was careful to put together a story from end to end, including making the files used available. I hope you can also replicate this case in your environment.

I will demonstrate how an IBM RPA bot can consume IBM BAMOE decision microservices. I must confess that I liked the result and am sure that combining these technologies can make a difference and further enhance the benefits of RPA projects.

The proposed case involves segmenting and registering customers in a web form. In short, the bot must execute the process in the following steps:

- Get all customers for processing from a CSV file.
- Send each customer's data to the decision microservice to obtain the score and segmentation
- Register the customer with the data in the WEB form

### Here you have access to the files of this case study, access the official publication posted in the [IBM community](https://community.ibm.com/community/user/automation/blogs/raul-mariano2/2024/10/04/ibmrpadmoecustomersegment)
