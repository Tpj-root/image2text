# image2text
Users to convert images containing textual data into editable text using advanced OCR (Optical Character Recognition)



Install it if you haven't

```
sudo apt install imagemagick

```


### Basic 





Counterclockwise 

```
convert input.jpg -rotate 90 output.jpg
```

Clockwise (CW) rotation  : use -90 instead

```
convert input.jpg -rotate -90 output.jpg

```









FILENAME: TEST_0.jpg

convert TEST_0.jpg -rotate -90 TEST_1.jpg

Convert to Grayscale

convert TEST_1.jpg -colorspace Gray Grayscale_2.jpg


Enhance Contrast and Remove Noise

convert Grayscale_2.jpg -contrast-stretch 5% -despeckle enhanced_image.jpg


Apply Thresholding to Extract Text Clearly

convert enhanced_image.jpg -threshold 50% threshold_image.jpg


Extract Alpha Channel (Transparency)

convert TEST_1.jpg -alpha extract alpha_image.png




| SL:NO | FILENAME   | DESCRIPTION | FILE |
|-------+------------+-------------+------|
|     1 | TEST_0.jpg | START       |      |
|     2 | TEST_1.jpg |             |      |
|     3 | TEST_2.jpg |             |      |
|     4 | TEST_3.jpg |             |      |
|     5 | TEST_4.jpg |             |      |
|     N | TEST_N.jpg | END         |      |
|FINAL  | TEST_N.txt | FINISH      |      |



