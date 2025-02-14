     Static Website Hosting using S3
Step-1) Create s3 bucket with unique name
Step-2) Upload website files & folders into bucket with public read-access
Step-3) Enable Static website hosting (in bucket properties)
  		index-document : index.html
			error-document : error.html
 After enabling static website hosting it generates end-point URL for our website
Step-4) Access our website using website endpoint url.
