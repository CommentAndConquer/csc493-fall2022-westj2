# Software Design

## Classes

### MainActivity

Class that provides camera functionalities of recording and storing videos and displaying a preview

#### Methods

##### onCreate

On app start. Binds UI to scripts and calls startCamera()

#### userAuthenticate

Calls devices screen lock authentication procedure.

#### startCamera

Accesses camera hardware, displays camera preview on screen. Binds camera 
so that it may be used for other use cases.

#### captureVideo

Begins video and audio recording and stores it in device storage

### GalleryActivity

Displays video thumbnails of videos recorded with the application in a grid on the screen. They are 
ordered by most recent first.



