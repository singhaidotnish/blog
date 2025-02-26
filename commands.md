###### X ffmpeg -i input.jpg -vf "crop=1130:864:(in_w-1130)/2:(in_h-864)/2" output.png
###### X ffmpeg -i input.jpg -vf "scale='min(1130,iw)':'min(864,ih)'" output.png
###### ✅ ffmpeg -i input.png -vf "scale=w=1130:h=864:force_original_aspect_ratio=decrease,pad=1130:864:(ow-iw)/2:(oh-ih)/2" output.png
