# handson_DL_UNIVR_2019

## 1 - Install Anaconda
https://docs.anaconda.com/anaconda/install/windows/

**Windows**

1.1 - Download the Anaconda Windows version (Python 3.7 version)
1.2 - Install using the default options
1.3 - open anaconda navigator

**Linux**  
https://www.digitalocean.com/community/tutorials/how-to-install-anaconda-on-ubuntu-18-04-quickstart

$ cd /tmp  
$ curl -O https://repo.anaconda.com/archive/Anaconda3-2019.07-Linux-x86_64.sh  
$ sha256sum Anaconda3-2019.07-Linux-x86_64.sh  
$ bash Anaconda3-2019.03-Linux-x86_64.sh 

$ source ~/anaconda3/bin/activate root  
$ anaconda-navigator  

## 2 - Create an Anaconda enviroment

2.1 - Click on Enviroments/Create  
2.2 - Give the name, chose Python 3.7, and click on Create  

## 3 - Install python packages

3.1 - on Anaconda Enviroments, select the new enviroment and chance "Installed" to "All"  
3.2 - Search and select the folowing packages: numpy, jupyter, ipython-notebook, and matplotlib, then click on Apply.

## 4 - Install Pytorch

4.1 - Install CUDA drivers if you have a NVIDIA GPU
4.2 - Select your configuration on https://pytorch.org/  
4.3 - Run the suggested command (e.g. conda install pytorch torchvision cudatoolkit=10.0 -c pytorch)

## 5 - Test the instalation and start coding

5.1 - Activate you enviroment running the command  
$ activate Enviroment_name  
5.2 - run the command  
$ jupyter notebook  
5.3 - run ./Codes/Instalation test.ipynb


