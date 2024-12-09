- This is a simple nodejs-app with a single test.
- The .github/workflows/ci-cd-pipeline.yaml has the main code for the pipeline.
- It has different steps setting up node, intalling dependencies, running tests, building docker image and **email notification** for success and failure of the CI/CD
- It also has secrets like DOCKER_USERNAME, DOCKER_PASSWORD, KUBECONFIG. EMAIL_USERNAME, EMAIL_PASSWORD.
- I have kept both sending and receiving mail id as same for now but they can be kept different.
- The mails received can be seen in **mails.png** and the contents of mail can be seen in **mail_data.png**.
- The data sent through mail can be updated and also other ways can be used like slack.