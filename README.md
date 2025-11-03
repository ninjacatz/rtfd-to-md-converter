# RTFD to Markdown Converter

## Guide
Set the user-defined variables in the script and run the script.

Required command line programs:
- pandoc
- imagemagick
- ffmpeg

## Description
Converts Apple '.rftd' directories to Github Markdown (preserving file attachments) from a selected folder recursively. Converted '.md' file will be named 'TXT.md' in a directory with the same name as the '.rtfd' directory and with attachment files, identical to an '.rftd' directory. Note that most '.rtf' formatting will be erased. 

Additionally, optionally converts Appled encoded images and videos to file formats of your choice.

