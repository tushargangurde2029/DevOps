Prerequisites: 
- An AWS account.
- An S3 bucket where you will host the HTML form.
- An email address that is verified in Amazon SES.
- The AWS CLI or SDK installed and configured on your local machine.
- The boto3 library installed in your local machine if you are using the AWS SDK.

Step 1: Create an S3 Bucket and Upload the HTML Form
- Create an S3 bucket and configure it to host a static website.
- Create an HTML form similar to this and upload it to the S3 bucket.
```html
<form id="contact-form" class="contact-form" name="contact-form" method="post" action="<API Gateway Endpoint URL>">
    <div class="row">
        <div class="col-sm-6">
            <div class="form-group">
                <input type="text" class="form-control" name="name" required="required" placeholder="Full Name">
            </div>
        </div>
        <div class="col-sm-6">
            <div class="form
