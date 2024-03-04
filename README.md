## **Analysis of Breathing Patterns Using Filtered Audio Data**

**Aim:**
The aim of this study is to analyze breathing patterns using audio data collected through a headset earphone with a strategically placed microphone inside a mask. Our goal is to determine the frequency range of the breathing information and develop a method to count breaths based on the intersection points between filtered and smoothed audio data.

**Approach:**
1. **Recording Audio Data:**
   Audio data was recorded using a headset earphone with a microphone strategically placed inside a mask to capture breathing sounds. The recorded audio file was saved for further analysis.

2. **Determining Sampling Rate:**
   The sampling rate of the recorded audio was determined using the `librosa` library in Python. This information is crucial for subsequent signal processing steps.

3. **Filtering Higher Frequencies:**
   Digital signal processing techniques were applied to filter out higher frequencies from the recorded audio data. A low-pass filter was utilized to allow frequencies below a certain cutoff while attenuating frequencies above that cutoff.

4. **Counting Breaths:**
   Two distinct graphs were presented: one representing the filtered audio data (red line) and the other signifying a heavily smoothed version (green line). The intersection points between these lines were utilized to determine the count of breaths. When the smoothed line intersected with the filtered line, it indicated a significant change in the audio signal, likely corresponding to a breath. By counting these intersection points, the number of breaths was estimated.

5. .**Analyzing Frequency Range:**
   Fourier transform was used to analyze the frequency content of the filtered audio data. This analysis helped identify the frequency range where breathing information is present.

**Results:**
The analysis revealed that the breathing information predominantly lies within a specific frequency range, as identified through Fourier transform. The method of counting breaths based on intersection points between filtered and smoothed audio data showed promising results, providing a non-invasive and automated approach to monitor breathing patterns.
** We have analyzing clean audio data, the process is straightforward. However, if there is noise or disturbances in the audio, various filters need to be applied for effective analysis.

**Conclusion:**
In conclusion, this study demonstrates the feasibility of analyzing breathing patterns using audio data collected through a headset earphone and a mask. By applying digital signal processing techniques and frequency analysis, we can extract valuable information about breathing behavior. The method of counting breaths based on intersection points between filtered and smoothed audio data offers a practical approach for monitoring breathing patterns in various settings, including healthcare and fitness applications. Further research and validation are warranted to refine the proposed methodology and enhance its accuracy and reliability.


<br>
<br>

#### By Aryan Raj 
#### IIT Jammu 
#### CSE Branch