# Project Progress

This document summarizes the work done on the NeoRefacer Gradio application.

## Features Added

- **Bulk Image Processing Mode:**
  - Added a new "Bulk Mode" tab to the Gradio interface.
  - Users can upload multiple image files for batch processing.
  - A "Reface Ratio" slider was added to control the amount of face swapping.
  - A preview gallery is displayed after processing, allowing users to see the refaced images.
  - Users can select/deselect images and download a zip file of the selected results.

- **Bulk Video Processing Mode:**
  - Added a new "Bulk Video Mode" tab to the Gradio interface.
  - Users can upload multiple video files for batch processing.
  - A "Reface Ratio" slider was added to control the amount of face swapping.
  - A preview gallery is displayed after processing, showing a frame from each refaced video.
  - Users can select/deselect videos and download a zip file of the selected results.

- **Error Handling and UI Improvements:**
  - Fixed a `ValueError` in the bulk processing modes.
  - Improved the user experience by providing progress indicators and status messages.
