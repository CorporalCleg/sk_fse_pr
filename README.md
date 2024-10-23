### Team #3 Project
#### Building a Robust Image Processing Pipeline Using SAM in Docker for Neural Network Training

*Team members:*
- Maksim Alymov
- German Devchich
- Denis Fatykhoph
- Maksim Smirnov

1. To build conatiner:
```bash
docker build . -t fse_test
```
2. To run container:
```bash
docker run -it -v <place_of_dataset>:/mnt/data -v $(pwd):/mnt/code fse_test:latest 
```
