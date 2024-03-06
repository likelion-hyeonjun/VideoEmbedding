# VideoEmbedding

## added files 

openclip/src/training/video_utils.py - to handle raw video file

## modified files

openclip/src/training/params.py - add new choice for param "dataset_type" (video), new param and "video_max_frames"
openclip/src/training/data.py - VideoCsvDataset Class added
openclip/src/training/train.py - add logic for handle 'video' dataset type

openclip/src/openclip/factory.py 
openclip/src/openclip/model.py - add "VideoClip" class and "TemporalEncoderCfg"
openclip/src/openclip/transformer.py - add "TemporalTransformer" class for Temproal Encoder 
