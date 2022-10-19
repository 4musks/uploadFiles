## About
'uploadFiles' Application to upload and download multiple files on Amazon Cloud

### Leveraging following AWS services 

- AWS Amplify Framework
- Amazon CloudFront
- Amazon S3
- Amazon Cognito
- AWS UI
- Node.JS
- React

## Getting Started

First install AWS Amplify CLI
`npm install -g @aws-amplify/cli`

Inside the project folder, initialize Amplify:
`amplify init`
> Project name example: uploadFiles

Add the authentication component
`amplify add auth`

Add the storage component
`amplify add storage`

> Select: Content (Images, audio, video, etc.)
> 
> Provide a label for this category or use the suggested one from the wizard.
>
> Select the option create/update from the list of actions

Add the application hosting
`amplify hosting add`

> Select Amazon CloudFront and S3. Define a new unique bucket name or use the suggested one.

Now, you can build the web app (front-end)

```bash
npm install
amplify push
amplify publish
```

The output of the `amplify publish` if all the deployment was done correctly is a URL
This URL is the web application URl where you can open from the browser to access your application.

### Prerequisites

To build this solution you must have:
- AWS account
- Permissions to create resources in the AWS account
- Node.js 16.x or higher

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

## References
https://github.com/aws-samples/s3uploader-ui
https://github.com/dabit3/awesome-aws-amplify

## Sample Images
https://www.pexels.com/search/restaurant/
