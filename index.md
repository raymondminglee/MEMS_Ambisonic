
# Introduction
---
While public interest for technologies that produce and deliver immersive VR content has been growing, the price point for these tools has remained relatively high.   
We present a low-cost, high-quality first-order ambisonics (FOA) microphone based on low-noise MEMS systems. We desinged and fabricated a 3D printed housing and using MEMS microphone in each of the 4 capsule to replicate such field microphone.   
To facilitate high resolution directivity response measurements, a low-cost, automatic rotating microphone mount using an Arduino was also designed.  
The automatic control of this platform was integrated into an in-house acoustic measurement library built in MATLAB, allowing the user to generate polar plots at resolutions down to 1.8°.  
Plor plot and frequency response of the proposed microphone was compared with current Sennheiser Ambeo VR mic available on the marcket. Subjective evaluations on recording using two different microphones were also conducted.  
<img src="pic/Intro.PNG?raw=true"/>
<br><br> 

#Hardware Design
---
## The Microphone
The microphone chosen was of the MEMS type, specifically the TDK InvenSense ICS-407201. These microphones exhibit omni-directionality when operated without any coupled hardware such as a Printed Circuit Board (PCB) or housing.  
<img src="pic/mic.PNG?raw=true"/>
<br><br>
## The Housing
The housing for the MEMS-based FOA mic prototype was 3D printed with Acrylonitrile Butadiene Styrene based filaments (ABS) using a high-end Stratasys Mojo 3D Printer at the NYU La Guardia Studio’s in Manhattan.  
<img src="pic/Housing.PNG?raw=true"/>
<br><br>
## Automatic Rotating Microphone Mount(ARM^2)
An automatic rotating microphone mount was designed in order to obtain the necessary polar response plots for the microphone.   
Manually measuring microphone directivity consumes considerable amount of time due to the inherent need to rotate the microphone some number of degrees repeatedly until at least 180° is reached for a single plot. Due to this necessity, automated rotating mounts are used to accurately and efficiently acquire the required data.  
<img src="pic/Platform.PNG?raw=true"/>
<br><br>

# Objective and Subjective Evaluation
---
## Frequency Response
The frequency response of the MEMS ambisonic in red was compared to the professional grade Sennheiser Ambeo VR mic. The MEMS solution showed a distinct and audible high frequency component above 10kHz.  
<img src="pic/FR.PNG?raw=true"/>
<br><br>
## Directionality
Using the ARM2 rotating platform, the directivity of a single capsule from our MEMS prototype was measured. A single capsule of the Sennheiser Ambeo VR was also measured for comparison. Both microphones in question were measured with their respective capsules facing the speaker at a fixed distance of 1m. The ARM2 was used to ensure that the capsule-speaker distance remains constant throughout the measurement cycle.  
<img src="pic/Polar.PNG?raw=true"/>  
the Sennheiser Ambeo VR microphone shows a clear cardioid polar pattern across all frequency ranges. This is likely due to the closed back construction of each capsule. The MEMS capsule directivity exhibits a cardioid-like response at frequencies above 4kHz due to the effects of the housing and microphone PCB mount.  
<br><br>
## Subjective Evaluation
Thirty-two participants were recruited from various university’s music technology programs, audio-related mailing lists and small groups of non-audio experienced subjects.  
<img src="pic/Subject.PNG?raw=true"/> 
<br><br>

# Conclusion
---
The prototype MEMS-based ambisonics microphone shows promise in its ability to capture high quality 3D audio at a fraction of the cost of commercially available devices.  
While the MEMS capsules directivity deviated from the desired cardioid response, its frequency and noise floor characteristics were generally well received.  
Results showed that subjects tended to perceive the MEMS recording as “thinner” and lacking bottom-end in general; however, most also noted that the MEMS capsules did not exhibit unfavorable signal-to-noise ratios, something often associated with micro-capsules

# AES Paper
---
We submitted our paper to the Audio Engineer Society (AES) 201 International Convention. The ful paper is linked below.
-[AES Paper](https://github.com/raymondminglee/Acoustic-Consulting/blob/master/doc/NEST%2Bm_summary.pdf)
