# Dataset-creation-using-Google-images

Finding dataset for training our deep learning models is always a challenge. Most of the time we need to manually download the images and annotate which is a time consuming task. 

This repo provides scripts which can automate the image download part. 

How to use?
===========

1. Open google images and type the keyword related to the image search eg. "Hotdog".
2. Scroll till the images appearing are relevant to your search.
3. Go to View -> Developer -> Javascript console. A Javascript console will get open.
4. Click on Console.
5. Enter the content of js_console.js line by line into console. After the last command, a file named "urls.txt" will get created in your Download directory.
6. Execute the download_images.py script with this command:

```sh
python download_images.py --urls "path to url.txt" --output "path to image download folder"
```