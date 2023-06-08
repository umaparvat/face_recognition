# Face REcognition Algorithm in Python
# To run
```
python detector.py --help
usage: detector.py [-h] [--train] [--validate] [--test] [-m {hog,cnn}]
                   [-f Filepath]

Recognize faces in an image

options:
  -h, --help    show this help message and exit
  --train       Train on input data
  --validate    Validate trained model
  --test        Test the model with an unknown image
  -m {hog,cnn}  Which model to use for training: hog(CPU), cnn(GPU)
  -f F          Path to an image with an unknown face

```
# Example
```commandline
python detector.py --validate
python detector.py --train -m="hog"
```
