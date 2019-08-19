# Image-Classifier

In this project, you'll train an image classifier to recognize different species of flowers.
Below files are part of this project.
1. Image Classifier Project ( html format of Image Classifier ipynb file)
2. train.py
3. predict.py


Commands to run these python files:

python train.py --data_dir flowers --arch vgg --gpu True --epochs 10 --hidden_units 100 --lr 0.001
python predict.py --image_path 'flowers/test/5/image_05159.jpg' --gpu True --mapper_json 'cat_to_name.json' --topk 3
