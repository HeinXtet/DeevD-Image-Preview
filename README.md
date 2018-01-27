## DeevD Image Preview

This is simple Image preview android open source  library written with kotlin.

#### Screen Shot
![demo]("https://github.com/HeinXtet/DeevDImagePreview/blob/master/demo.gif?raw=true")



#### How to use

1. Add your project gradle level 

   ```kotlin

   allprojects {
   		repositories {
   			maven { url 'htt ps://jitpack.io' }
   		}
   	}
   ```



2. Add your app level gradle

   ```
   dependencies {
   	       compile 'com.github.HeinXtet:DeevDialog:0.1.2'
   	}

   ```


### Easy to use



1. #### Preparation

```
var imageList = ArrayList<DialogImageData>() // id,description,imagePath,type
imagelist.add(1,"simple","image",true)

show_gallary.setOnClickListener {
            DeevDImagePreview
                    .setImageList(imageList)
                    .setAnimationRes(DeevDAnimation.PULSE_ANIMATION)
                    .setDefaultPosition(0)
                    .createImageDialog(this)
 }               
```

#### Done….

### License 

```
MIT License

Copyright (c) 2018 DevD

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```

