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

![image](https://github.com/anwesha2812/HackScriptFour/assets/78586680/5b38fd47-13be-4a4b-a5c6-cd5b4950b329)

![image](https://github.com/anwesha2812/HackScriptFour/assets/78586680/69d2e05d-d951-48c3-8eeb-5ff92b3937d7)

![image](https://github.com/anwesha2812/HackScriptFour/assets/78586680/873c47d6-65db-4536-ac1e-0b32d46c39b2)



