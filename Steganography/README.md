# Steganography method

My "To do" list for steganography

### Search string something with strings.
    strings example.jpg

### Search files in image.
    xxd example.jpg
> If there is something strange after FF D9(JPG end bytes), so we can use binwalk to extract hidden files.
    
    binwalk -e example.jpg

### Use Stegsolve.jar to analize:
 - Metadata.
 - Frames.
 - Different colors.
 - Offsets.
