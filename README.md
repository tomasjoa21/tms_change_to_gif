# pygifconvt

## Table of Contents
  * [Installation](#installation)
  * [Quick start](#quick-start)
  * [Features](#features)
  
## Installation

Download using pip via pypi.

```bash
$ pip install tms_change_to_gif --upgrade
  or
$ pip install git+https://github.com/tomasjoa21/tms_change_to_gif.git
```
(Mac/homebrew users may need to use ``pip3``)


## Quick start
```python
 >>> # from 패키지명.파일명 import 클래스명 as 별칭
 >>> from tms_change_to_gif.imgtogif import GifConverter
 >>> c = GifConverter("your original images path", 'your gif output path', (320,240))
 >>> c.convert_gif()
```

## Features
  * Python library to convert single oder multiple frame gif images
  * OpenCV does not support gif images.