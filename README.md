This is a generic template for diffusers pipeline. You will have to change the app.py and download.py and add your tokens to these files as well in addition to the docker file.

I have added     model.enable_attention_slicing(). If you don't want it remove it from the app.py file

# 🍌

# Deploy to Banana Serverless:

Three steps:
1. Create your own copy of this template repo. Either:
- Click "[Fork](https://github.com/bananaml/serverless-template/fork)" (creates a public repo)
- Click "[Use this Template](https://github.com/bananaml/serverless-template/generate)" (creates a private or public repo)
- Create your own repo and copy the template files into it

2. Install the [Banana Github App](https://github.com/apps/banana-serverless) to your new repo.

3. Login in to the [Banana Dashboard](https://app.banana.dev) and setup your account by saving your payment details and linking your Github.

From then onward, any pushes to the default repo branch (usually "main" or "master") trigger Banana to build and deploy your server, using the Dockerfile.
Throughout the build we'll sprinkle in some secret sauce to make your server extra snappy 🔥

It'll then be deployed on our Serverless GPU cluster and callable with any of our serverside SDKs:

- [Python](https://github.com/bananaml/banana-python-sdk)
- [Node JS / Typescript](https://github.com/bananaml/banana-node-sdk)
- [Go](https://github.com/bananaml/banana-go)

You can monitor buildtime and runtime logs by clicking the logs button in the model view on the Banana Dashboard](https://app.banana.dev)

<br>

## Use Banana for scale.
