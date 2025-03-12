# PMFS: Progressive Mouth-to-Face Synthesis for Realistic Talking Face Generation

## Click on the image to watch the demo

### Description:
- **Audio sample:** `M003_Angry_Level01_005`
- **First column:** Displays the mouth landmark of `M003_Angry_Level01_005`
- **Top three rows:** Use images from the MEAD dataset, including `M003`, `M030`, and `W024`
- **Bottom two rows:** Use images from the CREMA-D dataset, including `1001` and `1002`

### Notes:
- The **PMFS** model was trained only on the MEAD dataset but did not include `M003`, `M030`, or `W024` during training.
- The **CREMA-D** dataset was not used for training at all.

<a href="https://youtube.com/shorts/twI6TZMnpT8?feature=share">
  <img src="https://img.youtube.com/vi/twI6TZMnpT8/maxresdefault.jpg" width="600">
</a>

## Ablation study
Comparison of image synthesis quality under different conditions. The first two rows compare reference images from the driven video and a random video. The next two rows show results with and without warping. The last two rows illustrate the impact of background presence. The final image in each row is an enhanced heatmap visualization, highlighting synthesis errors.

![Ablation Study](assets/Ablation_All.png)
