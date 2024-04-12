#installation moviepy

   import moviepy.editor
   from pathlib import Path

    video_file = Path(#file name)
   
   video = moviepy.editor.videoFileclip(f'{#file name}')
   audio = video.audio
   audio.write_audiofile(f'{#file name}.mp3')
