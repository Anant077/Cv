Cv Ta-2

Implemented 3 algorithms names are - Harris Corner Detection , Shi-Tomasi corners and Blob Detectors.


1.Harris Corner Detector: Detects corners using intensity gradients; fast but can be noisy.
2.Shi-Tomasi Corner Detector: Improved Harris method using eigenvalues; more stable and good for tracking.
3.Blob Detector: Finds round or region-like features based on area and shape; great for spotting blobs, not corners.

Uploded original image and rest 3 images
Conclusion - If you're doing motion tracking, matching, or need corner reliability, go with Shi-Tomasi.
If you're detecting circular shapes, use Blob Detector.
If you want quick and basic corner detection, Harris is fine.
