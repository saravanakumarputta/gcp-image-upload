# gcp-image-upload-using-multer

## Step1
Clone the gcp-image-upload repository

## Step2
Open the terminal and navigate to clonned project.
Install the dependencies using `npm i`.

## Step 3
Download the key file from your GCP account using below steps.

1. Go to your GCP console or [here](https://console.cloud.google.com/).
2. Choose the project which you have created.
3. Then navigate to IAM and Admin option in the sidebar and select Service Accounts options.
4. Then click on the More icon at the end of your project and select Create Key.
5. Select as JSON click create. This will create the key and the JSON file will be downloaded in the browser.
6. Run `npm start` command to start the server.

* projectId - This can be fetched from the downloaded key file.
* bucket - Go to GCP and select the storage from the side menu. This will display all the storage buckets with their name.

## Final Step

Try calling the upload API and find the iuploaded file in the GCP storage engine.
