---
title: "How to print at NUS SoC"
date: 2021-03-01
draft: false
tags: ["English", "Tech"]
slug: ""
---
Adding printer to my mac is so hard. After trying it for 30 mins, I gave up. Then I searched on the Internet and got this tutorial.

```
# Login to Sunfire
ssh e0123456@sunfire.comp.nus.edu.sg

# Copy a local file to Sunfire
scp some_file.txt e0123456@sunfire.comp.nus.edu.sg:/home/e/e0123456/

# Copy a local directory to Sunfire
scp -r ./some_directory e0123456@sunfire.comp.nus.edu.sg:/home/e/e0123456/

# Convert PDF to PS file
pdftops input.pdf

# Print via Sunfire, use printer pstsb, also can use psts and pstsc
lpr -Ppstsb input.ps

# Convert PS file to 2 pages per sheet
psnup -2up input.ps output.ps
```

refer to [Aaron Choo's post](https://medium.com/@aaroncql/printing-via-sunfire-for-nus-soc-students-a879ce381630)