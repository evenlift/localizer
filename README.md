# localizer

Basic localizer for iconic views.  Tested on data sets including: bear and goat dataset, google weight dataset (iconic images of barbell from image search), youtube weight dataset (iconic images of barbells from YouTube).

### Design
This is built on top of pytorch, heavily borrowing optimizations from the fast.ai library.  Uses Resnet34.

### Training and next steps
Takes around 15 minutes to train at current HP on a P4000.  However, function was still converging.  Opportunity for additional performace simply by increasing epochs.
