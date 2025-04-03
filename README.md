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

convert TEST_0.jpg -rotate 90 TEST_1.jpg



| SL:NO | FILENAME   | DESCRIPTION | FILE |
|-------|------------|-------------|------|
|     1 | TEST_0.jpg | START       |      |
|     2 | TEST_1.jpg |             |      |
|     3 | TEST_2.jpg |             |      |
|     4 | TEST_3.jpg |             |      |
|     5 | TEST_4.jpg |             |      |
|     N | TEST_N.jpg | END         |      |
