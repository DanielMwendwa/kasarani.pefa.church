---
widget: blank
headless: true

# ... Put Your Section Options Here (title etc.) ...
title: Gallery
subtitle:
weight: 40 # section position on page
design:
    # Choose how many columns the section has. Valid values: 1 or 2.
    columns: '1'
    background:
        color: "#d6e8f0"
    # spacing:
    #     padding: ["20px", "20px", "80px", "20px"]
gallery_item:
    - album: gallery
      image: youth-wameshiba.jpg
      caption: Youth
    # - album: <ALBUM FOLDER>
    #   image: <IMAGE 2 NAME>.jpg
    #   caption: Write your image 2 caption here
---

{{< gallery album="gallery" >}}
