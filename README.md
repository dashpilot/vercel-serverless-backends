# Vercel Serverless Backends

Fetch and save data to S3 or a Github repo straight from your front-end app using Vercel functions.

This project provides a unified api to communicate with any S3-compatible storage (e.g. Amazon S3, Digitalocean Spaces, Linode Object Storage, etc). It currently uses Firebase Auth for authentication but can easily be adapted to your preferred auth system

# How To

1.  Clone this repo and connect to Vercel
2.  Set the following environment variables in Vercel:

S3_ENDPOINT: the endpoint of your S3-compatible storage (e.g. eu-central-1.linodeobjects.com)\
S3_BUCKET: your bucket\
S3_KEY: your S3 key\
S3_SECRET: your S3 secret

3.  Set the Firebase config in public/js/firebase.js to match your Firebase account
4.  Visit index.html to check out the demos
