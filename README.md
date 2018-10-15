# pythontesseract
Hello all,

This project is intended to enhance Tesseract with Python. Here's the file descriptions.

# jpn_vert3.traineddata

Based upon Tesseract 4.0 jpn_vert (best from tessdata), I enhanced traineddata a bit further.
(1) The training sentences were too formal. I included the casual conversations and have them trained.
    The initial error rate was 20%. I trained until it reaches less than 1%
(2) I trained couple of more Japanese fonts. (Please let me know if there it is).
(3) Now, this trainenddata is able to recognize the heart symbols. Originally, the entire sentence gets weird, once Tesseract runs into 
    heart symbols. I make the problem right by training heart symbols.

