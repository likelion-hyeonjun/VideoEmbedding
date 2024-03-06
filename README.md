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
   - (Specify the changes if any)

5. `openclip/src/openclip/model.py`:
   - Added `VideoClip` class.
   - Introduced `TemporalEncoderCfg`.

6. `openclip/src/openclip/transformer.py`:
   - Added `TemporalTransformer` class for Temporal Encoder.

## Usage
(Provide a brief description of how to use the new video embedding functionalities, including any necessary commands or steps.)

## Dependencies
(List any new dependencies required for the video embedding feature.)

## Contribution
This extension to OpenCLIP for video embedding is an ongoing project. Contributions, suggestions, and feedback are welcome.

(Contact information or steps for contribution.)
