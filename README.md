# DevopsProject

In this project, I used Docker, k8s, Helm and Jenkins.

<b>Step 1:</b>

Created an image for my Demo Python app and pushed it to my private ECR.

<b>Step 2:</b> 

Pulled the image using my aws credentials and deployed it into my k8s cluster.

<b>Step 3:</b>

Created a helm chart for the project and a Cronjob to renew the ECR token every 10 hours.

<b>Step 4:</b>

Used Jenkins job to build and push my image into my private ECR

<b>Step 5:</b>

Migrated the job to a Pipeline using Jenkinsfile


