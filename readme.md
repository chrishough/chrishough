![biography](https://github.com/chrishough/chrishough/blob/master/assets/biography.gif)
<!--
How did I make this video?

1. I made my video with https://codesandbox.io/s/github-profile-forked-6bbqx
2. Then I recorded my screen to gif on Mac with Quicktime and converted it to a gif
3. brew install ffmpeg
4. brew install gifsicle
5. ffmpeg -ss 30 -i biography.mov -vf "fps=10,scale=840:-1:flags=lanczos,split[s0][s1];[s0]palettegen[p];[s1][p]paletteuse" -loop 0 biography.gif

-->


