# video_stream_webrtc

A simple example of using webrtc to stream video from server (PYTHON) to client browser (JS).

Tested with .mp4 and .ts files

## Notes (Optional)

Use the following to convert .mp4 to .ts:

`ffmpeg -i abc.mp4 -c:v libx264 -c:a aac -b:a 160k -bsf:v h264_mp4toannexb -f mpegts -crf 32 pqr.ts`

No need of conversion to try out the example. Added just in case.
