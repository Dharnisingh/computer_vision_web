# computer_vision_web
Web based computer vision

# To build Container imagee:
git clone https://github.com/Dharnisingh/computer_vision_web.git

sudo docker build -t <app_docker_image> .

verify the image is built: sudo docker images

# To access the web cam of host use following command
docker run --device=/dev/video0:/dev/video0 -p 5000:5000 <app_docker_image>

# To access the application
Launch the web browser and type the URL: http://localhost:5000

