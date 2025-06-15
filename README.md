# PMFS: Progressive Mouth-to-Face Synthesis for Realistic Talking Face Generation

### The source code will be released soon.

<br/><br/><br/>

## Click on the image to watch the demo

### Description:
- **Audio sample:** `M003_Angry_Level01_005`
- **First column:** Displays the mouth landmark of `M003_Angry_Level01_005`
- **Top three rows:** Use images from the MEAD dataset, including `M003`, `M030`, and `W024`
- **Bottom two rows:** Use images from the CREMA-D dataset, including `1001` and `1002`

### Notes:
- The **PMFS** model was trained only on the MEAD dataset but did not include `M003`, `M030`, or `W024` during training.
- The **CREMA-D** dataset was not used for training at all.
- The video quality on YouTube may be reduced. You can watch the demo video directly at `assets/compare.mp4`.

<a href="https://youtube.com/shorts/ZnmVPP7X8kU?feature=share" target="_blank" rel="noopener noreferrer">
  <img src="https://img.youtube.com/vi/ZnmVPP7X8kU/maxresdefault.jpg" width="600">
</a>

## Comparison of Synthesized Image Quality with Different Emotions
<a href="https://youtu.be/QQ9e_SCqbb8" target="_blank" rel="noopener noreferrer">
  <img src="https://github.com/cxnam-vnuhcmus/PMFS/blob/main/assets/DifferenceEmotion.png" width="600">
</a>


## More sample
### Notes:
- The video quality on YouTube may be reduced. You can watch the demo video directly at folder `assets`.
  
<div align="center">
  <table>
    <tr>
      <td align="center">
        <p><b>Audio sample:</b> 1001_DFA_ANG_XX</p>
        <p><b>Target Face:</b> M003_Angry_Level01_005</p>
        <a href="https://youtube.com/shorts/_z_0_uXIVDQ?feature=share" target="_blank" rel="noopener noreferrer">
          <img src="assets/Thumbnail_M003Angry01005.jpg" width="300">
        </a>
      </td>
      <td align="center">
        <p><b>Audio sample:</b> M003_Angry_Level01_002</p>
        <p><b>Target Face:</b> Vietnamese</p>
        <a href="https://youtube.com/shorts/FGsDcgrDVWs?feature=share" target="_blank" rel="noopener noreferrer">
          <img src="assets/Thumbnail_VTV_M003Angry01005.jpg" width="300">
        </a>
      </td>
    </tr>
  </table>
</div>

## Ablation study
Comparison of image synthesis quality under different conditions. The first two rows compare reference images from the driven video and a random video. The next two rows show results with and without warping. The last two rows illustrate the impact of background presence. The final image in each row is an enhanced heatmap visualization, highlighting synthesis errors.

![Ablation Study](assets/Ablation_All.png)
