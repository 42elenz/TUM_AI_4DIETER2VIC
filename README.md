# TUM_AI_4DIETER2VIC

To Train the Model please enter the command:

Prequisit:
Make sure that you downloaded the dataset from https://stanfordmlgroup.github.io/competitions/mrnet/

Step 1:
python train.py -t acl -p coronal --epochs=15 --prefix_name coro_20
(Enter what you want to train for, for which plane, for how many epochs)

Step 2:
Make sure that all the models (coronal, axial and sagittal) are in the right folder. 

Than run:
python global_acl_classifier.py
