# savewibu
Place the Dockerfile in the same dir with package.json
Run:
docker build . -t <docker_image_name>:<tag-name>

Then run:
docker run -p 3000:3000 --name <docker-container-name> <docker_image_name>:<tag-name>

You can now browse the web app through http://localhost:3000
