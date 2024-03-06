# VideoEmbedding

## Overview
This project extends OpenCLIP to train video embedding model. 

## Added Files
- `openclip/src/training/video_utils.py`: Handles raw video files.

## Modified Files
1. `openclip/src/training/params.py`:
   - Added a new choice for the parameter `dataset_type`: `"video"`.
   - Introduced a new parameter: `video_max_frames`.

2. `openclip/src/training/data.py`:
   - Added `VideoCsvDataset` Class.

3. `openclip/src/training/train.py`:
   - Implemented logic to handle the 'video' dataset type.

4. `openclip/src/openclip/factory.py`:

5. `openclip/src/openclip/model.py`:
   - Added `VideoClip` class.
   - Introduced `TemporalEncoderCfg`.

6. `openclip/src/openclip/transformer.py`:
   - Added `TemporalTransformer` class for Temporal Encoder.

