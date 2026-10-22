# Recorder window for the IELTS practice site

A browser gives the microphone only to a page served over https. The practice site runs on plain http, so its
Speaking test opens this page in a small window: the student records each part here, and on Stop the recording is
handed back to the test page that opened the window (`postMessage`), which saves it. This page sends nothing anywhere
else and keeps nothing.

Published with GitHub Pages from `main`. The source lives with the site; change it there and copy it here.
