# Cattle-dataset

## Introduction
Our proposed dataset is big and contains a variety of scenes and lighting conditions that can better represent the real situation of the pasture. Expressly, We set up smart cameras in several pastures of Yibin and Qinghai. It took five months to monitor the daily life of cattle in different periods, seasons, scenarios and weather conditions to get video data. The intercepted surveillance video is sampled in real-time and then selected. Data with diverse scenes and significant variations in cattle movement were picked into the dataset.

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
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">#Train</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" rowspan="2" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:1.0000pt solid windowtext;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">#Test</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" rowspan="2" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:1.0000pt solid windowtext;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">Avg. Resolution</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">(</font></span><i><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-style:italic;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><font face="Times New Roman">H </font><font face="宋体">× </font><font face="Times New Roman">W</font></span></i><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">)</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" colspan="4" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:1.0000pt solid windowtext;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">Count Statistics</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">Total</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:1.0000pt solid windowtext;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">Min</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:1.0000pt solid windowtext;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">Ave</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:1.0000pt solid windowtext;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">Max</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;mso-border-left-alt:0.5000pt solid windowtext;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">UCSD</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">800</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">1,200</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">158 </font><font face="宋体">× </font><font face="Times New Roman">238</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">49,885</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">11</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">25</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">46</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;mso-border-left-alt:0.5000pt solid windowtext;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">UCF CC 50</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">-</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">50</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">2101 </font><font face="宋体">× </font><font face="Times New Roman">2888</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">63,974</font></span><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">94</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">1,279</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">4,543</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;mso-border-left-alt:0.5000pt solid windowtext;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">WorldExpo</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">3,380</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">600</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">576 </font><font face="宋体">× </font><font face="Times New Roman">720</font></span><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">199,923</font></span><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">1</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">50</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">253</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;mso-border-left-alt:0.5000pt solid windowtext;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">ShanghaiTech</span><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">_</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">A</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">300</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">182</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">589 </font><font face="宋体">× </font><font face="Times New Roman">868</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">241,677</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">33</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">501</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">3,139</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;mso-border-left-alt:0.5000pt solid windowtext;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">ShanghaiTech</span><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">_</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">B</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">400</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">316</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">768 </font><font face="宋体">× </font><font face="Times New Roman">1024</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">88,488</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">9</font></span><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">123</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">578</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr><tr><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:1.0000pt solid windowtext;mso-border-left-alt:0.5000pt solid windowtext;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">C</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">attle</span><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><span style="font-family:'Times New Roman';mso-spacerun:'yes';">&nbsp;</span><font face="Times New Roman">dataset </font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">493</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">357</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">864</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><span style="mso-spacerun:'yes';">&nbsp;</span></span><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="宋体">× </font><font face="Times New Roman">1317</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">1</span><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">8</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">,</span><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">403</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">3</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">2</span><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">2</font></span><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td><td valign="center" style="padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt ;border-left:none;mso-border-left-alt:none;
border-right:1.0000pt solid windowtext;mso-border-right-alt:0.5000pt solid windowtext;border-top:none;
mso-border-top-alt:0.5000pt solid windowtext;border-bottom:1.0000pt solid windowtext;mso-border-bottom-alt:0.5000pt solid windowtext;"><p class="MsoNormal" align="center" style="text-align:center;"><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">1</span><span style="font-family:宋体;mso-ascii-font-family:'Times New Roman';mso-hansi-font-family:'Times New Roman';
mso-bidi-font-family:'Times New Roman';font-size:9.0000pt;mso-font-kerning:1.0000pt;"><font face="Times New Roman">2</font></span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;">9</span><span style="font-family:'Times New Roman';mso-fareast-font-family:宋体;font-size:9.0000pt;
mso-font-kerning:1.0000pt;"><o:p></o:p></span></p></td></tr></tbody></table>

## Citation
If you use our dataset in your research, please cite with:

```
@article{wu2022mrvnet,
  title={Cattle counting estimation method based on multi-scale residual visual information fusion},
  author={Yang Wu，Wang Yinghui，Tan Yao，Feng Xin},
  journal={Application Research of Computers},
  volume={39},
  number={5},
  pages={5},
  year={2022},
}
```
