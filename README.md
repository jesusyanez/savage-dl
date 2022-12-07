# CDL

#### <p><i>1 package, 4 providers, 0 APIs</i></p> 


- Python 3 
- Works on all operating systems
- No API keys / credentials needed
- Auto extracts .zip files
- Auto extracts .rar files (requires 7zip)
- Removes compressed files after extraction

## Supported URLs

```txt
# Google Drive
https://drive.google.com/drive/folders/...?usp=sharing
https://drive.google.com/file/d/.../view?usp=sharing

# Dropbox
https://www.dropbox.com/s/.../...?dl=0(1)
https://www.dropbox.com/sh/.../...?dl=0(1)

# MediaFire
https://www.mediafire.com/file/.../.../file

# WeTransfer
https://wetransfer.com/downloads/.../...
```

## Usage
```python3
import lootdl

url1 = "https://drive.google.com/file/d/.../view?usp=sharing"
url2 = "https://www.dropbox.com/s/.../...?dl=0"
url3 = "https://www.mediafire.com/file/.../.../file"
url4 = "https://wetransfer.com/downloads/.../..."

download_list = [url1, url2, url3, url4]
download_path = "./Downloads/"

for url in download_list:
 lootdl.grab(url, download_path)
```




## Roadmap
- [X] Google Drive
- [X] Dropbox
- [X] MediaFire
- [X] WeTransfer
- [ ] Mega
 
 ## Acknowledgement
 
Code was borrowed from <a href="https://github.com/matthuisman/gdrivedl">gdrivedl</a>, <a href="https://github.com/Juvenal-Yescas/mediafire-dl">mediafire-dl</a>, and <a href="https://github.com/iamleot/transferwee">transferwee</a> to create lootdl.
