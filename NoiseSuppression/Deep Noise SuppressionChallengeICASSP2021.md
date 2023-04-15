# Deep Noise Suppression Challenge – ICASSP 2021

## Program dates: 
September 2020-January 2021



## Target
To foster innovation in the field of noise suppression to achieve superior perceptual speech quality.

## Two tracks
- Real – Time Denoising track:
The noise suppressor must take less than the stride time Ts (in ms) to process a frame of size T (in ms) on an Intel Core i5 quad-core machine clocked at 2.4 GHz or equivalent processors. For example, Ts = T/2 for 50% overlap between frames. The total algorithmic latency allowed including the frame size T, stride time Ts and any look ahead must be less than or equal to 40ms. For example, if you use a frame length of 20ms with a stride of 10ms resulting in an algorithmic delay of 30ms, then you satisfy the latency requirements. If you use a frame size of 32ms with a stride of 16ms resulting in an algorithmic delay of 48ms, then your method does not satisfy the latency requirements as the total algorithmic latency exceeds 40ms. If your frame size plus stride T1=T+Ts is less than 40ms, then you can use up to (40-T1)ms future information.
- Personalized Deep Noise Suppression (pDNS) track:
  - Satisfy Track 1 requirements
  - You will have access to 2 minutes speech of a particular speaker to extract speaker related information that might be useful to improve the quality of the noise suppressor. The enhancement must be done on the noisy speech test segment of the same speaker.
  - The enhanced speech using speaker information must be of better quality than enhanced speech without using the speaker information.



