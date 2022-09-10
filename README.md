# SRCNN/ FSRCNN & SRGAN

SRCNN = *Super Resolution Convolutional Neural Network* for IVUS Images

FSRCNN = *Fast Super Resolution Convolutional Neural Network* for IVUS Images

SRGAN = *Super Resolution Generative Adversarial Network* for IVUS Images

Based on the repository by [Zijin Luo](https://github.com/soapisnotfat/super-resolution)

## Training
- by executing 'main_train_psnr.py'
- Code: 
	**python main.py --m  [srcnn/fsrcnn/srgan]**
- add other arguments if required


## Testing
- by executing 'super_resolve.py'
- Code: 
	**python super_resolve**
- add other arguments if required


## Execution
- upload SRCNN_FSRCNN_SRGAN.ipynb file to Google Colaboratory
- follow instructions
- execute elements in the order they are included


## File Structure
- **SRCNN_FSRCNN_SRGAN.ipynb**: Google Colaboratory execution file
- **main.py**: training function
- **super_resolve.py**: testing function
- **SRCNN**: SRCNN model
- **FSRCNN**: FSRCNN model
- **SRGAN**: SRGAN model
- **dataset**: functions to prepare the dataset
- **SRImages**: some example images generated with the SRCNN/FSRCNN/SRGAN models and LR input images
- **trainedModels**: fully trained models of SRCNN/FSRCNN/SRGAN ('bare' & TL)
- **pretrainedModels**: pre-trained models utilized for transfer learning


