# HCI_UI_Study
This is the repo used for HCI user study as a backup plan. It provides interactive visualization of facial video and the predicted sequences from the Multi-task Affective state prediction.

## Usage
To process the raw prediction data (.cvs) and generate the figure, please use the jupyter notebook file:
```
jupyter notebook
open CSV_Normalization.ipynb
```
A figure of the sequence prediction can be saved, and set as the background of the 'waveform' container on the web.

To use the demo web, please first follow the instructions on [videojs_wavesurfer](https://github.com/collab-project/videojs-wavesurfer) to install the package.
Then put the video and prediction sequence figure to example folder,

```
cd videojs-wavesurfer/examples
open demo.html
```
