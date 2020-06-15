# [Towards Social Artificial Intelligence: Nonverbal Social Signal Prediction in A Triadic Interaction](http://domedb.perception.cs.cmu.edu/ssp.html)

Current version provides: 
- Haggling dataset from [Panoptic Studio](http://domedb.perception.cs.cmu.edu/index.html)
- Visualization code
- Testing code

## Requirements
- Python 3
- [PyTorch](https://pytorch.org/) tested on 1.1.0
- cv2
- PyOpenGL
- freeglut (use `sudo apt-get install freeglut3-dev` for ubuntu users)
- ffmpeg

## Download Pre-trained model

Run the following script to download the pretrained model. The checkpoint is saved under `./checkpoints/`.
```
sh ./scripts/download_haggling.sh
```

## Visualization
```
python glViewer.py
```

## License
[CC-BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/legalcode).
