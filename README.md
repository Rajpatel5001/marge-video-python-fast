# marge-video-python-fast
int terminal (for name and files)
for f in *.mp4; do echo "file '$f'" >> mylist.txt; done

for marging files 
ffmpeg -f concat -safe 0 -i mylist.txt -c copy output.mp4
