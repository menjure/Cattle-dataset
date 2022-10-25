# Cattle-dataset

## Introduction
Our proposed dataset is large and contains a variety of scenes and lighting conditions that can better represent the real situation of the pasture. Expressly, We set up smart cameras in several pastures of Yibin and Qinghai. It took five months to monitor the daily life of cattle in different periods, seasons, scenarios and weather conditions to get video data. The intercepted surveillance video is sampled in real-time and then selected. Data with diverse scenes and significant variations in cattle movement were picked into the dataset.

## Data
The format of the file is as follows：

```
data
 │  
 ├─test
 │   ├─ground_truth  // store the mat file of the corresponding image
 │   └─images
 │
 └─train
     ├─ground_truth
     └─images
```

Statistics of different crowd counting datasets and cattle dataset as follows:

<table class="MsoTableGrid" border="1" cellspacing="0" style="border-collapse:collapse;margin-left:6.7500pt;margin-right:6.7500pt;
border:none;mso-border-left-alt:0.5000pt solid windowtext;mso-border-top-alt:0.5000pt solid windowtext;
mso-border-right-alt:0.5000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;mso-border-insideh:0.5000pt solid windowtext;
mso-border-insidev:0.5000pt solid windowtext;mso-padding-alt:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;"><tbody><tr><td valign="center" rowspan="2" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;mso-border-left-alt:0.5000pt solid windowtext;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:1.0000pt solid windowtext;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">Dataset</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" rowspan="2" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:1.0000pt solid windowtext;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">#Train</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" rowspan="2" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:1.0000pt solid windowtext;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">#Test</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" rowspan="2" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:1.0000pt solid windowtext;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">Avg. Resolution</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">(</span><i><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-style:italic;
font-size:9.0000pt;mso-font-kerning:1.0000pt;">H × W</span></i><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">)</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" colspan="4" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:1.0000pt solid windowtext;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">Count Statistics</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">Total</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:1.0000pt solid windowtext;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">Min</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:1.0000pt solid windowtext;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">Ave</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:1.0000pt solid windowtext;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">Max</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;mso-border-left-alt:0.5000pt solid windowtext;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">UCSD</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">800</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">1,200</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">158 × 238</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">49,885</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">11</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">25</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">46</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;mso-border-left-alt:0.5000pt solid windowtext;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">UCF</span><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">_</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">CC</span><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">_</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">50</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">-</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">50</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">2101 × 2888</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">63,974</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">94</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">1,279</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">4,543</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;mso-border-left-alt:0.5000pt solid windowtext;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">WorldExpo</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">3,380</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">600</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">576 × 720</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">199,923</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">1</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">50</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">253</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;mso-border-left-alt:0.5000pt solid windowtext;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">ShanghaiTech_A</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">300</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">182</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">589 × 868</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">241,677</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">33</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">501</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">3,139</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;mso-border-left-alt:0.5000pt solid windowtext;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">ShanghaiTech_B</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">400</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">316</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">768 × 1024</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">88,488</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">9</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">123</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">578</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;mso-border-left-alt:0.5000pt solid windowtext;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">C</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">attle</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><span style="mso-spacerun:'yes';">&nbsp;</span>dataset </span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">493</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">357</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">864</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><span style="mso-spacerun:'yes';">&nbsp;</span></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><font face="Times New Roman">× 1317</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">1</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">8</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">,</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">403</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">3</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">2</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">2</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">1</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">2</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">9</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr></tbody></table>

## Citation
If you use our dataset in your research, please cite with:

```
@article{math10203856,
  author = {Zhong, Minyue and Tan, Yao and Li, Jie and Zhang, Hongming and Yu, Siyi},
  title = {Cattle Number Estimation on Smart Pasture Based on Multi-Scale Information Fusion},
  journal = {Mathematics},
  volume = {10},
  year = {2022},
  number = {20},
｝
```
