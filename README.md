This repo employs Chris Choy's 3d-R2N2 and BO Yang 3d-RecGAN as well as Jmaher19 construction in order to construct 3d representations of heads. This is is a work in progress, the demo and requirements are the same as previous work in the project and is listed in the requirement files in the sub folders. 3D-R2N2 works in a theano p36 environment on a p2x large machine environment and 3D-ReaGAN in tensor flow. To run the demo follow the read me for the 3D-R2N2 folder. Please stay tuned. To run the demo after installation python demo.py nameofoutputfile.obj.  To runn this on a p2Xlarge ec2 instance, clone the git hub on the instance in a theano p36 on deep learning maching. to install
 cd 3D-R2N2  
conda install pygpu
pip install -r requirements.txt
cp .theanorc ~/.theanorc

please ignore the py3-theano enviroment install in the read me of the 3D-R2N2 folder it is out of date and will break the system. running in the native p2xlarge theano p36 enviroment is better.  Running the demo 

enter

python demo.py prediction.obj

or rename prediction to the name of your output voxel mesh.

