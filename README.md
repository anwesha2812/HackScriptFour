# HackScriptFour
![image](https://github.com/anwesha2812/HackScriptFour/assets/78586680/862fbe7f-16b2-45ab-a039-2f20970f0b29)

Given: Image Dataset containing forms and invoices

Proposed solution
1. Perform OCR on image
2. Document-type detection using Zero-shot classification (classes: Form/Invoice)
3. Preprocess the image- use OpenCV to draw boxes around each token(word)
4. Cluster the boxes using their co-ordinates- horizontally, vertically and diagonally to find out data label and input.
5. Assign weights/priority to each token such top right corner has the maximum weight and bottom left has the least.
6. Creating Safety-check on top of Clustering using Deep NLP techniques.
7. Displaying result on webapp.


Results:

![image](https://github.com/anwesha2812/HackScriptFour/assets/78586680/de599dff-67b5-4de2-a83a-36e94e42dd50)

