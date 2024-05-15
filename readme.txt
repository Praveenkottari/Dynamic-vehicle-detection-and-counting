#for testing with webcam
python tracker1.py --weights bestn-fp16.tflite --source 1 --save-vid

#for testing with recorded video
python tracker.py --weights bestn-fp16.tflite --source "video_name.mp4" --save-vid
