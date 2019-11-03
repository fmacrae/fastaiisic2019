# Starter for deploying [fast.ai](https://www.fast.ai) models on [Render](https://render.com) or you can put it on any internet facing cloud machine.   I used lightsail with a 1Gb memory footprint and 1Gb swap file.  It might still be running here:  http://3.13.88.192:5001/

This repo can be used as a starting point to deploy [fast.ai](https://github.com/fastai/fastai) models on Render.

The sample app described here is up at https://fastai-v3.onrender.com. Test it out with bear images!

You can test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5001:5001 fastai-v3
```

The guide for production deployment to Render is at https://course.fast.ai/deployment_render.html.

Please use [Render's fast.ai forum thread](https://forums.fast.ai/t/deployment-platform-render/33953) for questions and support.
<<<<<<< HEAD
# fastaiisic2019
=======


I've also punted this up to https://hub.docker.com/r/finlayatdocker/fastaiisic2019 if you just want to launch a pre built version.
>>>>>>> 443055bfa2aedac3a7c72425365d8a83f745c193
