###### ffmpeg -i input.jpg -vf "crop=1130:864:(in_w-1130)/2:(in_h-864)/2" output.png
###### ffmpeg -i input.jpg -vf "scale='min(1130,iw)':'min(864,ih)'" output.png
