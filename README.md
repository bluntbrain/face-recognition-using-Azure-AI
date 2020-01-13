# face-recognition-using-Azure-AI
travvex is flask application that recognises face and can extract text from pictures. It can also translate the text extracted to different languages using Neural Machine Translation.

Computer Vision and Translator API by Microsoft
Users of this website, whether travelling for business or pleasure, will be able to upload photos of street signs taken from their phones and see the translation of the sign. To build the application, I used Computer Vision API and Translator Text API to read the text and translate it respectively.

Face Detection usng Microsoft Azure Face API
One of the more common challenges companies look to solve revolves around facial recognition. This could be apps which allow for a form of mixed reality, where hats or other features are placed on a face. Or maybe you're looking to guess how someone is feeling at the moment to track feedback. Or, of course, you might be looking to determine who someone is in a picture. Microsoft Face API can help you with all of those challenges.

In this project I used a Flask application to test Face API. Created a simple UI for training facial recognition, and then test it out by trying to detect a couple of faces.In order to recognize people in an image you need to first train up your model. This is done by uploading pictures containing the face of the person you wish to be able to identify, and specifying a name.
