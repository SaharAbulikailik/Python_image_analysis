# Smooth_Prediction_with_SAM

SmoothPred is a Python code that demonstrates the use of the Segment Anything model for predicting and generating smooth image segmentations. 
It utilizes the Smooth Tiled Predictions algorithm to handle large images and achieve seamless predictions.

## Pipeline

1. Install the required dependencies:
   - czifile
   - patchify
   - jupyter_bbox_widget
   - roboflow
   - dataclasses-json
   - supervision
   - segment-anything

2. Download the pre-trained model checkpoint from the Segment Anything repository.

3. Load and preprocess the image data.

4. Run the smooth prediction code using the Segment Anything model and the Smooth Tiled Predictions algorithm.

5. Post-process the predictions as needed.

6. Save or display the final predicted segmentation results.

## Usage

Make sure that you have the smooth_tiled_prediction.py file, your image, and cloned SAM model in your workspace.


## References
- Segment Anything: [arXiv:2304.02643](https://arxiv.org/abs/2304.02643)
- Smoothly Blend Image Patches: [GitHub](https://github.com/Vooban/Smoothly-Blend-Image-Patches)
- Code adapted from Python for Microscopists: [GitHub](https://github.com/bnsreenu/python_for_microscopists/tree/master/229_smooth_predictions_by_blending_patches)

