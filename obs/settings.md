# OBS Settings

## `Settings → Output` tab
* Output Mode: Advanced

## `Settings → Output → Recording` tab
**Everything default except:**

* Video encoder: AV1 (if you don't have AV1, choose H.265/HEVC)
* Rate control: Constant QP, or Variable Bitrate with Target Quality if you really care about file space

---

## `Settings → Video` tab

* Base (Canvas) Resolution: whatever resolution your monitor is  
* Output (Canvas) Resolution: what you want the output to be. E.g. some people downscale from 4k or 1440p to 1080p or 720p.
* Downscale Filter: Bicubic
* Common FPS Values: 60
