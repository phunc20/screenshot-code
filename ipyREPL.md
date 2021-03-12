In [3]: import pytesseract

In [4]: import cv2

In [5]: img = cv2.imread("133259895_3877619965589690_6870628584488561859_o.jpg")

In [6]: import matplotlib.pyplot as plt

In [7]: plt.imshow(img);



In [15]: !pacman -S tesseract-data-eng
error: you cannot perform this operation unless you are root.

In [16]: text = pytesseract.image_to_string(img)

In [17]: text
Out[17]: 'for i in range(len(instr)):\n\nG D)\n\n \n\x0c'

In [18]: print(text)
for i in range(len(instr)):

G D)





In [19]: plt.imshow(img); plt.show();
q
