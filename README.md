# LDI
Based on the assignment text, I have made the following assumptions:

Document is monolingual.
Document doesn't have code-switching and code-mixing.
It's straightforward to implement a transformer token classifier to deal with code-mixed document challenges, but I prefer sequence classification since an annotated dataset is available, and the assignment probably does not require addressing code-mixed cases.

To solve the LID problem, I decided to start with Naive Bayes classification and then try Logistic regression and finally implement a transformer-based solution. Transformer model is evidently superior to two other methods and this superiority will become more apparent as more data amasses.
