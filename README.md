# Trabalho-Multidisciplinar PARTE 01

# Extração dos Frames com FFMPEG

## Guia de Instalação: https://phoenixnap.com/kb/ffmpeg-windows

## Comandos:
cd .\videos\
ffmpeg -i video_01.mp4 -vf "select=lte(n\,239)" -vsync vfr frames\video_01\frame_%04d.png
ffmpeg -i video_02.mp4 -vf "select=lte(n\,239)" -vsync vfr frames\video_02\frame_%04d.png
ffmpeg -i video_03.mp4 -vf "select=lte(n\,239)" -vsync vfr frames\video_03\frame_%04d.png
ffmpeg -i video_04.mp4 -vf "select=lte(n\,239)" -vsync vfr frames\video_04\frame_%04d.png
ffmpeg -i video_05.mp4 -vf "select=lte(n\,239)" -vsync vfr frames\video_05\frame_%04d.png
ffmpeg -i video_06.mp4 -vf "select=lte(n\,239)" -vsync vfr frames\video_06\frame_%04d.png