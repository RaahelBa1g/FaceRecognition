For implementing-:




Installing the required dependencies-:
> Open the command prompt
> navigate to folder (inside the folder)
> enter-:
```
pip install opencv-contrib-python
conda install -c menpo dlib
pip install imutils
```

At present I have seeded the dataset folder with Elon musk , Leonardo DiCaprio and steve jobs images , You can fill in your photos and test that out 

Here we are producing embeddings, You can use them to train your own model(try experimenting)
```
python test.py
```
You can find your embeddings in output folder after running the model
During the process of training you can view which part of the image (face) is being converted to embeddings

