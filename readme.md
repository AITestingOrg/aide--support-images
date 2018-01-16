# Support Images for AIDE
This repository contains all support Docker support images used throughout the AIDE project.

## Creating New Images
* Create your Dockerfile in a new folder with the same name as your image.
* Build your container
'''bash
docker build -t <MY_HUB_USERNAME>/<IMAGE_NAME> .
'''
* Ensure your container runs as expected.
'''bash
docker run --name <IMAGE_NAME> -t <IMAGE_NAME>
'''
* Login to Docker Hub
'''bash
docker login
'''
* Push your new image to Docker
'''bash
docker push <MY_HUB_USERNAME>/<IMAGE_NAME>

## Updating Existing Images
* Update your Dockerfile.
* Build your container
'''bash
docker build -t <MY_HUB_USERNAME>/<IMAGE_NAME> .
'''
* Ensure your container runs as expected.
'''bash
docker run --name <IMAGE_NAME> -t <IMAGE_NAME>
'''
* Login to Docker Hub
'''bash
docker login
'''
* Push your new image to Docker
'''bash
docker push <MY_HUB_USERNAME>/<IMAGE_NAME>