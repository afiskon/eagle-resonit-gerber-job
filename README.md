# resonit\_gerber.cam

Job for generating Gerber files from CadSoft Eagle's project, specialized for
[rezonit.ru][rz] service. Based on [this tutorial (in Russian)][tut].

Usage:

1. Download resonit\_gerber.cam;
2. Create a directory named "resonit\_gerber" in your project's directory;
3. Open your PCB in Eagle;
4. File -> CAM Processor...;
5. File -> Open -> Job...;
6. Open resonit\_gerber.cam;
7. Click on "Process Job" button;
8. If asked "Layer 'Holes' is active but, but layer 'Drills' is not active! Is
it OK?" click "Yes";
9. Archive resonit\_gerber folder and upload the archive to resonit.ru;

Tested on Eagle 7.7.0 Standard Edition for Linux (64 bit).

[rz]: http://www.rezonit.ru/
[tut]: http://www.rezonit.ru/support/directions/eagle/index.php
