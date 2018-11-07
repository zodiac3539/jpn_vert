# Enhancing jpn_vert.traineddata and jpn.traineddata
Hello all,

This project is to enhance Tesseract 4's capability to recognize Japanese better. As you all know, Tesseract uses LSTM, which is a machine-learning technique to recognize characters from a picture file. This means that (a) the sentences / fonts are very important and (b) how much do you have your machine trainned is also important. 

## jpn_ver3.traineddata

Based upon Tesseract 4.0 jpn_vert (best from tessdata), I enhanced traineddata a bit further.

* The training sentences were too formal. I included the casual conversations and have them trained. The initial error rate was 20%. I trained until it reaches less than 1%.

* I trained couple of more Japanese fonts. (Please let me know if there it is).

* Now, this trainenddata is able to recognize the heart symbols. Originally, the entire sentence gets weird, once Tesseract runs into heart symbols. I make the problem right by training heart symbols.


## jpn_ver4.traineddata

Finally, there has been a major improvement.

* Add more fonts - VL, Komorebi

* Add more expressions that are frequently used in a casual conversations.

* Trained almost 200,000 cycles. The character level error rate is less than 1%.
