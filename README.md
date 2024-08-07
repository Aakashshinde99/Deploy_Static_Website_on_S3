
# Deploy_Static_Website_on_S3

A hands-on project to practice Terraform with AWS and create a - - static website hosted on S3.
Here are the steps of what I did:

- Setup Terraform Provider: Created provider.tf file to define AWS provider.

- Defined S3 Bucket: Created main.tf to define the S3 bucket resource.

- Set Bucket Name: Created variables.tf for the bucket name.

- Initialized Terraform: Ran terraform init, terraform plan, and terraform apply to set up the S3 bucket.

- Created Website Files: Developed index.html for the main page and error.html for error handling.

- Configured S3 Bucket: Added resources to manage bucket ownership, access control, and upload HTML files.

- Deployed the Website: Ran terraform plan and terraform apply to upload files and make the website public.

- Result:

🎉Successfully hosted static website on S3!🎉
