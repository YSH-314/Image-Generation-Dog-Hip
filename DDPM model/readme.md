# Install Packages
## Create a new environment in Anaconda and activate, open the Anaconda prompt, and type the following commands  
1. move the path to D: type the command d:, after entering the prompt shows D:\>
2. conda create --prefix /{environment path without D:}/{env name-self-defined env name} python=3.8 numpy  
3. returns Proceed ([y]/n)? y  
4. conda activate /{environment path}/{env name}   
5. conda install jupyter notebook  
6. returns Proceed ([y]/n)? y  

## copy the folder 'denoising_diffusion_pytorch' to the following path \{environment path}\{env name}\Lib\site-packages

## Open Jupyter Notebook
! pip install torch==2.0.1+cu118 torchvision==0.15.2+cu118 --extra-index-url https://download.pytorch.org/whl/cu118    
! pip install einops==0.6.1   
! pip install matplotlib==3.7.2   
! pip install scipy   
! pip install imageio==2.31.1   
! pip install tqdm==4.66.1   
! pip install pandas==2.0.3   
! pip install ema_pytorch   
! pip install accelerate==0.21.0   
! pip install pytorch_fid   

