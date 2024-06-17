# WL_fMRI
This is WL_fMRI of Tengwen


## Word Learning from Context (fMRI Version)

### Relabeling DICOM files
Use [this website](https://dicomviewer.net/local?datasources=dicomlocal) to identify which images were obtained

DICOM folder structure:
- sub
  - session 1
    - 3 Plane
    - MPRAGE
    - WLfMRI_1
    - WLfMRI_2
    - WLfMRI_3
    - WLfMRI_4
    - WM_1
    - WM_2
   - session_2
     - 3 Plane
     - MPRAGE
     - Resting
     - Langloc
     - Cogflex
### Rename raw data folder with rename_ser.py
### Creating BIDS with Heudiconv
Run script: /Users/tengwenfan/Desktop/bids_test/construct_bids_tf.sh

