# NCF-Net-1.0

The development of a deep learning model (NCF-Net 1.0) to semantically identify tow wrinkling behaviour in carbon fibre NCF images (baseline - capture individual tow sections). The resulting prediction masks (binary images) are then used to return localised regions of interest (ROIs) within the NCF image (individual tows).

Outputs: Baseline - Deep Learning model to extract tow segments from RGB images (of macroscopic wrinkles) taken using DSLR/mobile phone cameras.

Extension: Using localised ROIs (tow masks) to extract fibre paths from individual tows


Current Files:
Deep Learning Code - Python 3.6, TensorFlow 2.5 - for training and predictions
Post-processing Code - MATLAB 2021a (Toolboxes: Image Processing, Signal Processing, Deep Learning and Computer Vision) - for loading in image datastores, analysing prediction masks
