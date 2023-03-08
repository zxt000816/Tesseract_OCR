# run this command to build the docker image for main.ipynb
docker run --gpus all --shm-size 16G -p 8888:8888 -v C:\Users\zyf13\Desktop\test\Tesseract_OCR:/app zyf0706/cv-pytorch:0.0.5