# vfxtd-code-test
Code test for potential VFX Technical Directors

## Instructions

Please fork this repo and issue a pull request.  You can then push code exercising the following tasks in a Maya environment. 

- Generate a dialog listing all of Laika's movies.  Provide 5 columns for each row: movie name, release date, domestic gross, movie poster icon, and a "camera" button.
- Dialog's title should be _Laika Movies_
- Should be able to sort list by Name and Release Date (click column header to sort)
- Each row's "camera" button should create a simple camera rig in Maya.  Maya rig will be composed as follows:
  - cameraGroup (transform) with two children--cameraMover (transform) and camera (camera)
  - camera position and rotation should be controlled by cameraMover
  - camera's attributes should be locked and not visible in the channel editor so that it can't be modified directly
  - camera should use the movie poster as an image plane

__Bonus:__
- Enable drag/drop so that dragging/dropping a row into the maya interface to create the camera rig for that row.


## Requirements

- We are currently running maya 2016 sp6 and PyQt4 but any Maya < 2017 should work
- Python + PyQt4 or PySide
- Adhere to pep8 guidelines
- One week max start to finish

