# TUM_AI_4DIETER2VIC

To train the model please enter the command:

Prequisit:
Make sure that you downloaded the dataset from https://stanfordmlgroup.github.io/competitions/mrnet/

Step 1:
python train.py -t acl -p coronal --epochs=15 --prefix_name model42
(Enter what you want to train for, for which plane, for how many epochs, always use the prefix_name model42)

Put the 3 trained models in the folder model_15_epochs

Step 2:
Make sure that all the models (coronal, axial and sagittal) are in the right folder. 

Than run:
python global_acl_classifier.py


The buisness model is appended in the presentation.
