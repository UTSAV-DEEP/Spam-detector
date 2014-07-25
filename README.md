Spam-detector
=============
ABOUT THE SOFTWARE:

It is a java based desktop application which classifies (text) files into spam or ham. The project works on naive bayesian machine learning algorithm. It becomes better and better classifier by learning process, provided it is trained correctly.
The software does not require any installation, however to use it, java must be installed in your system.

PREREQUISITE:

1. Java should be installed in the system.

HOW TO USE:

1. Unzip the downloaded zip file and mark spamDetector.jar as executable.
2. Run the file spamDetector.jar by either using terminal or by just double clicking it.
3. To run this software from terminal, go insied the unzipped directory then run this command:
   java -jar spamDetector.jar
   Running from terminal will give better appearance.
   (The images inside the buttons will not be visible when you run it by double click,
   but it will be visible when you run it from command line or terminal. Everything else will remain same).
4. Now the desktop application is ready to use.
5. Open a (text) file that you want to view the contents of file and see if it is spam or ham.
6. If the classifier classifies the file as:
   (a) Spam- then the color of the text field (just below the buttons) turns red and the text field says "SPAM" in bold.
   (b) Ham- then the color of the text field (just below the buttons) turns green and the text field says "HAM" in bold.
7. If you think that the file is actually a SPAM but it is classified as a HAM, then you can mark the file as spam by clicking on the button        "Mark as Spam".
   If you think that the file is not a SPAM but it is classified as a SPAM, then you can mark the file as ham by clicking on the button "Mark as    Ham".
8. In step 6 the spam detector displays the appropriate message in the text field and it learns through this so that it can classify the files in    a better way (this is an example of  machine learning).
9. If you want to make the software to forget everything it has learned so far you can press "Reset" button.
