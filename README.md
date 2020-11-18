# Dockerfile
Dockerfile.txt for bioinformatics, with latest ubuntu, miniconda, jupyter lab, NGS kit, and R.

1. Build dokcer image: docker build -t image_tag -< Dockerfile.txt

2. Build container from image by docker desktop or command: docker run -it -p 9005:8888 image_tag  
##-v for file mapping

3. Run jupyter inside the container terminal: jupyter lab --allow-root /root  --port=8888 --no-browser --ip=0.0.0.0

4. Open browser and go to http://localhost:9005/lab

Youtube vedio: https://www.youtube.com/watch?v=W5auJq2FYAo

