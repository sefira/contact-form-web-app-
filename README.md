# contact-form-web-app-
Created a contact form with html that connects to AWS lambda through the AWS API Gateway to send notification to a verified entity.
View presentatioh here: https://docs.google.com/presentation/d/1dOEqPS48EgZDJbd4eKuRMtABLDYBUqnNQwwJz0KlSYI/edit?usp=sharing 
To achieive this:
- created the frontend contact form with html (ref contact_form.html)
- set up a verified entity in AWS Simple Email Service.
- created an API with a post method that connects to a lambda function ((ref lambda_handler))
- set up an IAM role for the API to access lambda
- created a lambda function to send a notification to the verified email when the form is filled.
- tested with postman.

