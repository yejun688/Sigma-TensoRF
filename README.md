# Sigma-TensoRF
YEJUN

IRMV Lab
## Installing Requirements
'''
conda create -n SigmaRF python
conda activate SigmaRF
pip install -r requirements.txt
'''

### Datasets
Please arrange the datasets in a folder named "data". The following are the download links to the datasets:
+ [NeRF Synthetic](https://drive.google.com/drive/folders/128yBriW1IG_3NJ5Rp7APSTZsJqdJdfc1) (Link to Google Drive)
+ [LLFF](https://drive.google.com/drive/folders/128yBriW1IG_3NJ5Rp7APSTZsJqdJdfc1) (Link to Google Drive)
+ [Tanks & Temples](https://dl.fbaipublicfiles.com/nsvf/dataset/TanksAndTemple.zip) (Download will start after clicking on link)

We note that we use a processed version of Tanks & Temples, and the `intrinsics.txt` file of "Ignatius" was incompatible with our code. Please manually replace it with the following contents:
```