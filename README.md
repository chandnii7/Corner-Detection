# Corner Detection And Feature Comparison

Objectives:
1. Gaussian Noise and Smoothing
2. Harris Corner Detection
3. Non-maximum Suppression
4. Corner Localization
5. Extract Feature Vectors using HOG
6. Feature Comparison
<br/>

Interactively controlled parameters:
* Variance for gaussian (scale)
* Smoothing value for gaussian smoothing (filter size)
* Neighborhood size for computing the correlation matrix
* Weight of the trace in the Harris corner detection
* Threshold value for non-maximum Suppression
<br/>

Program was implemented using Python and OpenCV. Refer the report for further implementation details and instructions to run the code:
<a href="https://github.com/chandnii7/CornerDetection/blob/main/doc/Report_A2_Chandni_Patel.pdf">View Report</a>
<br/><br/>

### Results:
1. Corner Detection with implemented Harris corner detection function and OpenCV:
<table>
<tr>
<td>
<img src="https://github.com/chandnii7/CornerDetection/blob/main/data/out1.jpg" height="300" width="300"/>
</td>
<td>
<img src="https://github.com/chandnii7/CornerDetection/blob/main/data/out2.jpg" height="300" width="300"/>
</td>
</tr>
<tr>
<td>
Implemented Harris Corner Detection
</td>
<td>
OpenCV
</td>
</tr>
</table>
<br />

2. Corner Detection with Gaussian Noise (variance = 1) and Gaussian Smoothing (filter size = 15):
<table>
<tr>
<td>
<img src="https://github.com/chandnii7/CornerDetection/blob/main/data/out3.jpg" height="300" width="300"/>
</td>
<td>
<img src="https://github.com/chandnii7/CornerDetection/blob/main/data/out4.jpg" height="300" width="300"/>
</td>
</tr>
<tr>
<td>
Implemented Harris Corner Detection
</td>
<td>
OpenCV
</td>
</tr>
</table>
<br />

3. Feature Comparison with Features Extracted:
<table>
<tr>
<td>
<img src="https://github.com/chandnii7/CornerDetection/blob/main/data/out5.jpg" height="300" width="250"/>
</td>
<td>
<img src="https://github.com/chandnii7/CornerDetection/blob/main/data/out6.jpg" height="300" width="250"/>
</td>
</tr>
<tr>
<td>
Image 1
</td>
<td>
Image 2
</td>
</tr>
</table>
<br />
