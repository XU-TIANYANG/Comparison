# Comparision
Compare performances of algorithms on Objcet Tracking Benchmarks (SOT/MOT...)
 
[**SOT (single object tracking)**](https://github.com/JudasDie/Comparison/README.md)

[**Deepfake detection**](https://github.com/JudasDie/Comparison/blob/master/Deepfake%20detection.md)


<!-- #### Contents
- [Single Objetc Tracking]() -->


- **Single Object Tracking (SOT)**  
   - Download Papers (.zip) in [ECCV20](), [CVPR20](https://drive.google.com/file/d/1eBlzvliOIq508uYeAT5YjPPc_5ZSATXd/view?usp=sharing), [AAAI20](https://drive.google.com/file/d/1EKQHhWVcbzbNQ_4bEIBDP0QOj44vcSMG/view?usp=sharing), [CVPR2019](https://drive.google.com/file/d/1M-bWTbtktgha3FinC8YBuIlGZi29BJDP/view?usp=sharing), [ICCV19](https://drive.google.com/file/d/1SGRayZUYMnWm0KdR6xtJr6Jj8aiAsgY_/view?usp=sharing), [AAAI19](https://drive.google.com/file/d/1-h8aqzIprta5jv6RpDThMMCkUaVprNTg/view?usp=sharing), [ECCV18](https://drive.google.com/file/d/1WtAMh6DBlpQ7_5AYFeoABo4rOoMMSblK/view?usp=sharing), [CVPR18](https://drive.google.com/file/d/1OsWnHf-b4ZW1C_5GH6EKx5I8qyHg6Fd0/view?usp=sharing), [ICCV17](https://drive.google.com/file/d/19FtR_qHYMcK2rPmGBzr9HknQr5ru-rgt/view?usp=sharing), [CVPR17](https://drive.google.com/file/d/1xyC7OSbs1wN3Vgy69mU99O1H2sMdf11n/view?usp=sharing), [Others](https://drive.google.com/file/d/1fXQi9N0f7mAvsVV11ksfFOCewjol5Dml/view?usp=sharing)


<table class="center">
   </font>
<font size="1" face="Courier New" >
   <tr>
      <td rowspan="2";><b>Conf.<b></td>
      <td rowspan="2"><b>Trackers<b></td>
      <td><b>OTB13/15<b></td>
      <td><b>LASOT<b></td>
      <td><b>GOT10K<b></td>
      <td><b>TrackingNet<b></td>
      <td><b>VOT20<b></td>
      <td><b>VOT19<b></td>
      <td><b>VOT18<b></td>
      <td><b>VOT17<b></td>
      <td><b>VOT16<b></td>
      <td><b>UAV123<b></td>
      <td><b>NFS<b></td>
      <td><b>TC128<b></td>
      <td><b>OxUvA<b></td>
      <td><b>VOT18LT<b></td>
   </tr>
   <tr>
      <td><font size="1"> <b><sup>AUC/Prep.<sup><b></td>
      <td><font size="1"> <b><sup>Succ./Prep.<sup><b></td>
      <td><font size="1"> <b><sup>AO/SR0.5/SR0.75<sup><b></td>
      <td><font size="1"> <b><sup>Succ./Prep.<sup><b></td>
      <td><font size="1"> <b><sup>A/R/EAO<sup><b></td>
      <td><font size="1"> <b><sup>A/R/EAO<sup><b></td>
      <td><font size="1"> <b><sup>A/R/EAO<sup><b></td>
      <td><font size="1"> <b><sup>A/R/EAO<sup><b></td>
      <td><font size="1"> <b><sup>A/R/EAO<sup><b></td>
      <td><font size="1"> <b><sup>Succ./Prep.<sup><b></td>
      <td><font size="1"> <b><sup>Succ./Prep.<sup><b></td>
      <td><font size="1"> <b><sup>Succ./Prep.<sup><b></td>
      <td><font size="1"> <b><sup>M/TPR/TNR<sup><b></td>
      <td><font size="1"> <b><sup>Pr/Re/F<sup><b></td>
   </tr>
   <tr>
      <td rowspan="3"><b>ECCV20<b></td>
      <td><b><a href="https://arxiv.org/pdf/2006.10721.pdf">Ocean</a><b></td>
      <td><sub>-/(0.684/0.920)<sub></td>
      <td><sub>0.560/0.566<sub></td>
      <td><sub>0.611/0.721/-<sub></td>
      <td>-</td>
      <td><sub>0.470/0.715/0.286<sub></td>
      <td><sub>0.594/0.316/0.350<sub></td>
      <td><sub>0.592/0.117/0.489<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2003.11014.pdf">KYS</a><b></td>
      <td><sub>-/(0.695/)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.636/0.751/0.515<sub></td>
      <td><sub>0.740/0.688<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.609/0.143/0.462<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.635/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123670426.pdf">PGNet</a><b></td>
      <td><sub>-/(0.691/0.892)<sub></td>
      <td><sub>0.531/0.605<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.618/0.192/0.447<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.679/0.610/0.642<sub></td>
   </tr>
   <!-- <tr>
      <td><b><a href="https://arxiv.org/pdf/1910.08681.pdf">SPARK</a><b></td>
      <td><sub>-/(0.701/0.891)<sub></td>
      <td><sub>0.648/0.722<sub></td>
      <td><sub>0.649/0.728/0.597<sub></td>
      <td><sub>0.812/0.800<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.609/0.220/0.408<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr> -->
   <tr>
      <td rowspan="8"><b>CVPR20<b></td>
      <td><b><a href="https://arxiv.org/pdf/2004.00830v1.pdf">MAML</a><b></td>
      <td><sub>(0.714/-)/(0.712/-)<sub></td>
      <td><sub>0.523/-<sub></td>
      <td>-</td>
      <td><sub>0.757/-<sub></td>
      <td>-</td>
      <td><sub>0.637/0.421/0.295<sub></td>
      <td><sub>0.635/0.220/0.392<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1911.12836.pdf">Siam R-CNN</a><b></td>
      <td><sub>-/(0.701/0.891)<sub></td>
      <td><sub>0.648/0.722<sub></td>
      <td><sub>0.649/0.728/0.597<sub></td>
      <td><sub>0.812/0.800<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.609/0.220/0.408<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.649/0.834<sub></td>
      <td><sub>0.639/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://arxiv.org/pdf/1911.08862v2.pdf">D3S</a><b></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.597/0.676/0.462<sub></td>
      <td><sub>0.728/0.664<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.640/0.150/0.489<sub></td>
      <td>-</td>
      <td><sub>0.660/0.131/0.493<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2003.12565v1.pdf">PrDiMP</a><b></td>
      <td><sub>-/(0.696/-)<sub></td>
      <td><sub>0.598/-<sub></td>
      <td><sub>0.634/0.738/0.543<sub></td>
      <td><sub>0.758/0.704<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.618/0.165/0.442<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.680/-<sub></td>
      <td><sub>0.635/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1907.12006v3.pdf">ROAM</a><b></td>
      <td><sub>-/(0.681/0.908)<sub></td>
      <td><sub>0.447/0.445<sub></td>
      <td><sub>0.465/0.532/0.236<sub></td>
      <td><sub>0.670/0.623<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.543/0.195/0.380<sub></td>
      <td><sub>0.599/0.174/0.441<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2003.06761.pdf">SiamBAN</a><b></td>
      <td><sub>-/(0.696/0.910)<sub></td>
      <td><sub>0.514/0.598<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.602/0.396/0.327<sub></td>
      <td><sub>0.597/0.178/0.452<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.631/0.833<sub></td>
      <td><sub>0.594/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2004.06711v1.pdf">SiamAttn</a><b></td>
      <td><sub>-/(0.712/0.926)<sub></td>
      <td><sub>0.560/0.648<sub></td>
      <td>-</td>
      <td><sub>0.752/-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.63/0.16/0.470<sub></td>
      <td>-</td>
      <td><sub>0.68/0.14/0.537<sub></td>
      <td><sub>0.650/0.845<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Du_Correlation-Guided_Attention_for_Corner_Detection_Based_Visual_Tracking_CVPR_2020_paper.pdf">CGACD</a><b></td>
      <td><sub>-/(0.713/0.922)<sub></td>
      <td><sub>0.518/0.626<sub></td>
      <td>-</td>
      <td><sub>0.711/0.693<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.615/0.173/0.449<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.633/0.833<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td rowspan="7"><b>AAAI20<b></td>
      <td><b><a href="https://www.aaai.org/Papers/AAAI/2020GB/AAAI-XuY.5104.pdf">SiamFC++</a><b></td>
      <td><sub>-/(0.683/-)<sub></td>
      <td><sub>0.544/-<sub></td>
      <td><sub>0.595/0.695/0.479<sub></td>
      <td><sub>0.754/0.705<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.587/0.183/0.426<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://aaai.org/Papers/AAAI/2020GB/AAAI-WangN.1288.pdf">POST</a><b></td>
      <td><sub>(0.672/0.884)/(0.678/0.907)<sub></td>
      <td><sub>0.481/0.463<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
       <td><sub>0.629/0.800<sub></td>
       <td><sub>-<sub></td>
       <td><sub>0.563/0.781<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1912.00597.pdf">SPS</a><b></td>
      <td><sub>(0.703/0.911)/(0.692/0.902)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.612/0.169/0.434<sub></td>
      <td>-</td>
      <td><sub>0.625/0.158/0.459<sub></td>
       <td><sub>-<sub></td>
       <td><sub>0.600/-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://www.aiide.org/ojs/index.php/AAAI/article/view/6956/6810">RPOT</a><b></td>
      <td><sub>-/(0.687/0.914)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1911.11170.pdf">MetaRTT</a><b></td>
      <td><sub>-/(0.655/0.890)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-/-/0.346<sub></td>
      <td><sub>0.569/0.809<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.597/0.800<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1912.08531.pdf">GlobalT</a><b></td>
      <td><sub>-<sub></td>
      <td><sub>0.521/0.527<sub></td>
      <td>-</td>
      <td><sub>0.704/0.656<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.603/0.574/0.633<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1909.02959.pdf">DROL</a><b></td>
      <td><sub>-/(0.715/0.937)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>0.746/0.708<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.616/-/0.481<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.652/0.855<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.687/0.650<sub></td>
   </tr>
   <tr>
      <td rowspan="12"><b>CVPR19<b></td>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Deeper_and_Wider_Siamese_Networks_for_Real-Time_Visual_Tracking_CVPR_2019_paper.pdf">SiamDW</a><b></td>
      <td><sub>(0.689/-)/(0.674/-)<sub></td>
      <td><sub>0.384/-<sub></td>
      <td><sub>0.416/-/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-/-/0.242<sub></td>
      <td><sub>-/-/0.270<sub></td>
      <td><sub>-/-/0.246<sub></td>
      <td><sub>-/-/0.304<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1812.05050.pdf">SiamMask</a><b></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.642/0.295/0.387<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.670/0.233/0.442<sub></td>
       <td>-</td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_SiamRPN_Evolution_of_Siamese_Visual_Tracking_With_Very_Deep_Networks_CVPR_2019_paper.pdf">SiamRPN++</a><b></td>
      <td><sub>-/(0.696/0.923)<sub></td>
      <td><sub>0.496/0.569<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.733/0.694<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.600/0.234/0.414<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.613/0.807<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Danelljan_ATOM_Accurate_Tracking_by_Overlap_Maximization_CVPR_2019_paper.pdf">ATOM</a><b></td>
      <td><sub>-/(66.7/87.9)<sub></td>
      <td><sub>0.514/0.505<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.703/0.648<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.590/0.204/0.401<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.650/-<sub></td>
      <td><sub>0.590/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Fan_Siamese_Cascaded_Region_Proposal_Networks_for_Real-Time_Visual_Tracking_CVPR_2019_paper.pdf">CRPN</a><b></td>
      <td><sub>(0.663/-)/(0.675/-)<sub></td>
      <td><sub>0.455/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.669/0.619<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-/-/0.273<sub></td>
      <td><sub>0.594/-/0.363<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_SPM-Tracker_Series-Parallel_Matching_for_Real-Time_Visual_Object_Tracking_CVPR_2019_paper.pdf">SPM</a><b></td>
      <td><sub>(0.693/-)/(0.687/0.899)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.580/0.300/0.338<sub></td>
      <td><sub>0.620/0.210/0.434<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>

   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Gao_Graph_Convolutional_Tracking_CVPR_2019_paper.pdf">GCT</a><b></td>
      <td><sub>(0.670/0.873)/(0.648/0.854)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-/-/0.269<sub></td>
      <td>-</td>
      <td><sub>0.508/0.732<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Dai_Visual_Tracking_via_Adaptive_Spatially-Regularized_Correlation_Filters_CVPR_2019_paper.pdf">ASRCF</a><b></td>
      <td><sub>-/(0.692/0.922)<sub></td>
      <td class="red"><sub>0.359/0.337<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.494/0.234/0.328<sub></td>
      <td><sub>0.563/0.187/0..391<sub></td>
       <td>-</td>
       <td><sub>-<sub></td>
       <td><sub>0.603/0.825<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1904.01828.pdf">UDT</a><b></td>
      <td><sub>-/(0.632/0.831)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>0.53/-/0.301<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.541/0.717<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1904.01772.pdf">TADT</a><b></td>
      <td><sub>(0.680/0.896)/(0.660/0.866)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>0.550/-/0.299<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.562/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Sun_ROI_Pooled_Correlation_Filters_for_Visual_Tracking_CVPR_2019_paper.pdf">RPCF</a><b></td>
      <td><sub>(0.713/0.954)/(0.690/0.929)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.500/0.234/0.316<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub><sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_CVPR_2019/papers/Kart_Object_Tracking_by_Reconstruction_With_View-Specific_Discriminative_Correlation_Filters_CVPR_2019_paper.pdf">OTR</a><b></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub><sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td rowspan="11"><b>ICCV19<b></td>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2019/papers/Bhat_Learning_Discriminative_Model_Prediction_for_Tracking_ICCV_2019_paper.pdf">DiMP</a><b></td>
      <td><sub>-/(0.684/-)<sub></td>
      <td><sub>0.569/-<sub></td>
      <td><sub>0.611/0.717/0.492<sub></td>
      <td><sub>0.740/0.687<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.597/0.153/0.440<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.654/-<sub></td>
      <td><sub>0.620/-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2019/papers/Li_GradNet_Gradient-Guided_Network_for_Visual_Object_Tracking_ICCV_2019_paper.pdf">GradNet</a><b></td>
      <td><sub>-/(0.639/0.861)<sub></td>
      <td><sub>0.365/0.351<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.507/0.375/0.247<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2019/papers/Choi_Deep_Meta_Learning_for_Real-Time_Target-Aware_Visual_Tracking_ICCV_2019_paper.pdf">MLT</a><b></td>
      <td><sub>(0.621/-)/(0.611/-)<sub></td>
      <td><sub>0.368/-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.498/-<sub></td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2019/papers/Yan_Skimming-Perusal_Tracking_A_Framework_for_Real-Time_and_Robust_Long-Term_Tracking_ICCV_2019_paper.pdf">SPLT</a><b></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.622/0.498/0.776<sub></td>
      <td><sub>0.633/0.600<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_Learning_Aberrance_Repressed_Correlation_Filters_for_Real-Time_UAV_Tracking_ICCV_2019_paper.pdf">ARCF</a><b></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.473/0.666<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_Bridging_the_Gap_Between_Detection_and_Tracking_A_Unified_Approach_ICCV_2019_paper.pdf">BGDT</a><b></td>
      <td><sub>(0.656/-)/(0.647/-)<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.586/-<sub></td>
      <td><sub>0.515/-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhang_Learning_the_Model_Update_for_Siamese_Trackers_ICCV_2019_paper.pdf">UpdateNet</a><b></td>
      <td>-</td>
      <td><sub>0.475/-<sub></td>
      <td>-</td>
      <td><sub>0.677/0.625<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-/-/0.393</td>
      <td>-</td>
      <td><sub>0.610/0.206/0.481<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2019/papers/Wiyatno_Physical_Adversarial_Textures_That_Fool_Visual_Object_Tracking_ICCV_2019_paper.pdf">PAT</a><b></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2019/papers/Xu_Joint_Group_Feature_Selection_and_Discriminative_Filter_Learning_for_Robust_ICCV_2019_paper.pdf">GFS-DCF</a><b></td>
      <td><sub>(0.722/0.965)/(0.693/0.932)<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.6090/0.5657<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.511/0.143/0.397<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2019/papers/Lukezic_CDTB_A_Color_and_Depth_Visual_Object_Tracking_Dataset_and_ICCV_2019_paper.pdf">CDTB</a><b></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Zheng_Fast-deepKCF_Without_Boundary_Effect_ICCV_2019_paper.pdf">fdKCF</a><b></td>
      <td><sub>(0.705/0.908)/(0.675/0.891)<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-/-/0.265<sub></td>
      <td><sub>-/-/0.347<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="3"><b>AAAI19<b></td>
      <td><b><a href="https://www.aaai.org/ojs/index.php/AAAI/article/view/4862/4735">Re2EMA</a><b></td>
      <td><sub>-/(0.652/0.832)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.521/0.695<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://faculty.ucmerced.edu/mhyang/papers/aaai2019_tracking.pdf">ANT</a><b></td>
      <td><sub>-/(0.670/0.905)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1712.05231.pdf">LDES</a><b></td>
      <td><sub>(0.677/0.810)/(0.643/0.783)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   </tr>
   <tr>
      <td rowspan="12"><b>ECCV18<b></td>
      <td><b><a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Goutam_Bhat_Unveiling_the_Power_ECCV_2018_paper.pdf">UPDT</a><b></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.532/0.182/0.378<sub></td>
      <td><sub>0.550/-<sub></td>
      <td><sub>0.541/-<sub></td>
      <td><sub>0.622/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Zheng_Zhu_Distractor-aware_Siamese_Networks_ECCV_2018_paper.pdf">DaSiam</a><b></td>
      <td><sub>-/(-/0.88)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.560/0.340/0.326<sub></td>
      <td><sub>0.610/0.220/0.411<sub></td>
      <td><sub>0.586/0.796<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/mengdan_zhang_Visual_Tracking_via_ECCV_2018_paper.pdf">SACF</a><b></td>
      <td><sub>(0.713/0.938)/(0.693/0.917)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Yingjie_Yao_Joint_Representation_and_ECCV_2018_paper.pdf">RTINet</a><b></td>
      <td><sub>-/(0.682/)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>0.57/-/0.298<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.602/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Eunbyung_Park_Meta-Tracker_Fast_and_ECCV_2018_paper.pdf">MetaT</a><b></td>
      <td><sub>-/(0.662/0.888)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>0.519/-/0.317<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Xiankai_Lu_Deep_Regression_Tracking_ECCV_2018_paper.pdf">DSLT</a><b></td>
      <td><sub>(0.683/0.934)/(0.660/0.909)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-/-/0.332<sub></td>
      <td><sub>0.530/0.746<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.587/0.807<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Liangliang_Ren_Deep_Reinforcement_Learning_ECCV_2018_paper.pdf">DRLIS</a><b></td>
      <td><sub>-/(0.671/0.909)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.590/0.818<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Ilchae_Jung_Real-Time_MDNet_ECCV_2018_paper.pdf">RTMDNet</a><b></td>
      <td><sub>-/(0.650/0.885)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.528/0.772<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.563/0.788<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Boyu_Chen_Real-time_Actor-Critic_Tracking_ECCV_2018_paper.pdf">ACT</a><b></td>
      <td><sub>(0.657/0.905)/(0.625/0.859)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-/-/0.275<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Yunhua_Zhang_Structured_Siamese_Network_ECCV_2018_paper.pdf">StructSiam</a><b></td>
      <td><sub>(0.638/0.880)/(0.621/0.851)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-/-/0.264<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Tianyu_Yang_Learning_Dynamic_Memory_ECCV_2018_paper.pdf">MemTrack</a><b></td>
      <td><sub>(0.642/0.849)/(0.626/0.820)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>0.53/-/0.273<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ECCV_2018/papers/Xingping_Dong_Triplet_Loss_with_ECCV_2018_paper.pdf">SiamTri</a><b></td>
      <td><sub>(0.629/0.834)/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-/-/0.215<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td rowspan="14"><b>CVPR18<b></td>
      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Song_VITAL_VIsual_Tracking_CVPR_2018_paper.pdf">VITAL</a><b></td>
      <td><sub>(0.710/0.950)/(0.691/0.917)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-/-/0.323<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Sun_Learning_Spatial-Aware_Regressions_CVPR_2018_paper.pdf">LSART</a><b></td>
      <td><sub>-/(0.672/0.923)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.493/0.218/0.323<sub></td>
      <td>-</td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Li_High_Performance_Visual_CVPR_2018_paper.pdf">SiamRPN</a><b></td>
      <td><sub>-/(0.637/0.851)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-/-/0.243<sub></td>
      <td><sub>0.56/-/0.344<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Choi_Context-Aware_Deep_Feature_CVPR_2018_paper.pdf">TRACA</a><b></td>
      <td><sub>(0.652/0.898)/(0.603/0.816)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Learning_Attentions_Residual_CVPR_2018_paper.pdf">RAS</a><b></td>
      <td><sub>(0.670/0.892)/(0.642/-)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-/-/0.283<sub></td>
      <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/He_A_Twofold_Siamese_CVPR_2018_paper.pdf">SASiam</a><b></td>
      <td><sub>(0.677/0.896)/(0.657/0.865)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.500/0.459/0.236<sub></td>
      <td><sub>0.540/-/0.291<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Li_Learning_Spatial-Temporal_Regularized_CVPR_2018_paper.pdf">STRCF</a><b></td>
      <td><sub>-/(0.683/0.842)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>0.550/-/0.313<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>0.601/-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhu_End-to-End_Flow_Correlation_CVPR_2018_paper.pdf">FlowTrack</a><b></td>
      <td><sub>(0.689/0.921)/(0.655/0.881)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>0.570/-/0.341<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Meshgi_Efficient_Diverse_Ensemble_CVPR_2018_paper.pdf">DEDT</a><b></td>
      <td><sub>-/(0.690/0.810)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_SINT_Robust_Visual_CVPR_2018_paper.pdf">SINT++</a><b></td>
      <td><sub>-/(0.574/0.768)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Sun_Correlation_Tracking_via_CVPR_2018_paper.pdf">DRT</a><b></td>
      <td><sub>(0.720/0.953)/(0.699/0.923)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Multi-Cue_Correlation_Filters_CVPR_2018_paper.pdf">MCCT</a><b></td>
      <td><sub>(0.695/0.914)/(0.714/0.928)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>0.580/-/0.393<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>0.596/0.797<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Tang_High-Speed_Tracking_With_CVPR_2018_paper.pdf">MKCF</a><b></td>
      <td><sub>(0.641/0.835)/-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>0.455/0.532<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Dong_Hyperparameter_Optimization_for_CVPR_2018_paper.pdf">HP</a><b></td>
      <td><sub>(0.629/-)/(0.601/0.796)<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
       <td><sub>-<sub></td>
   </tr>
   <tr>
      <td rowspan="13"><b>ICCV17<b></td>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2017/papers/Song_CREST_Convolutional_Residual_ICCV_2017_paper.pdf">CREST</a><b></td>
      <td><sub>(0.673/0.908)/(0.623/0.837)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.514/-/0.283<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2017/papers/Huang_Learning_Policies_for_ICCV_2017_paper.pdf">EAST</a><b></td>
      <td><sub>(0.629/-)/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2017/papers/Fan_Parallel_Tracking_and_ICCV_2017_paper.pdf">PTAV</a><b></td>
      <td><sub>(0.663/0.894)/(0.635/0.849)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.544/0.741<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2017/papers/Galoogahi_Learning_Background-Aware_Correlation_ICCV_2017_paper.pdf">BACF</a><b></td>
      <td><sub>-/(0.630/-)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.652/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2017/papers/Teng_Robust_Object_Tracking_ICCV_2017_paper.pdf">TSN</a><b></td>
      <td><sub>-/(0.644/0.808)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2017/papers/Supancic_Tracking_as_Online_ICCV_2017_paper.pdf">Ptracker</a><b></td>
      <td><sub>-/(0.730/-)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2017/papers/Guo_Learning_Dynamic_Siamese_ICCV_2017_paper.pdf">DSiam</a><b></td>
      <td><sub>(0.656/0.891)/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2017/papers/Sun_Non-Rigid_Object_Tracking_ICCV_2017_paper.pdf">SPKCF</a><b></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w28/Zhu_UCT_Learning_Unified_ICCV_2017_paper.pdf">UCT</a><b></td>
      <td><sub>(0.641/0.904)/(0.611/0.849)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w28/Bottger_The_Benefits_of_ICCV_2017_paper.pdf">PWS</a><b></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w28/He_Correlation_Filters_With_ICCV_2017_paper.pdf">CFWCR</a><b></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-/-/0.303<sub></td>
      <td><sub>0.58/-/0.391<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w28/Li_Integrating_Boundary_and_ICCV_2017_paper.pdf">IBCCF</a><b></td>
      <td><sub>(0.660/-)/(0.630/)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.48/-/0.209<sub></td>
      <td><sub>0.511/-/0.266<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.537/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w28/Yang_Recurrent_Filter_Learning_ICCV_2017_paper.pdf">RFL</a><b></td>
      <td><sub>-/(0.581/)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.48/-/0.23<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td rowspan="11"><b>CVPR17<b></td>
      <td><b><a href="http://openaccess.thecvf.com/content_cvpr_2017/papers/Danelljan_ECO_Efficient_Convolution_CVPR_2017_paper.pdf">ECO</a><b></td>
      <td><sub>-/(0.700/-)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.54/-/0.374<sub></td>
      <td><sub>0.537/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.605/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_cvpr_2017/papers/Valmadre_End-To-End_Representation_Learning_CVPR_2017_paper.pdf">CFNet</a><b></td>
      <td><sub>(0.618/0.753)/(0.589/0.711)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_cvpr_2017/papers/Mueller_Context-Aware_Correlation_Filter_CVPR_2017_paper.pdf">CACF</a><b></td>
      <td><sub>-/(0.598/0.810)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_Robust_Visual_Tracking_CVPR_2017_paper.pdf">RaF</a><b></td>
      <td><sub>(0.615/0.919)/(0.565/0.851)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_Multi-Task_Correlation_Particle_CVPR_2017_paper.pdf">MCPF</a><b></td>
      <td><sub>(0.677/0.916)/(0.628/0.873)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.545/0/774<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_cvpr_2017/papers/Choi_Attentional_Correlation_Filter_CVPR_2017_paper.pdf">ACFN</a><b></td>
      <td><sub>(0.607/0.860)/(0.575/802)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_Large_Margin_Object_CVPR_2017_paper.pdf">LMCF</a><b></td>
      <td><sub>(0.643/0.892)/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_cvpr_2017/papers/Yun_Action-Decision_Networks_for_CVPR_2017_paper.pdf">ADNet</a><b></td>
      <td><sub>-/(0.646/0.880)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_cvpr_2017/papers/Lukezic_Discriminative_Correlation_Filter_CVPR_2017_paper.pdf">CSRDCF</a><b></td>
      <td><sub>-/(0.587/0.733)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>0.51/-/0.338<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_cvpr_2017/papers/Han_BranchOut_Regularization_for_CVPR_2017_paper.pdf">BranchOut</a><b></td>
      <td><sub>-/(0.683/0.919)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <!-- <tr>
      <td><b><a href="http://openaccess.thecvf.com/content_cvpr_2017/papers/Yeo_Superpixel-Based_Tracking-By-Segmentation_Using_CVPR_2017_paper.pdf">AMCT</a><b></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-/-/0.303<sub></td>
      <td><sub>0.58/-/0.391<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr> -->
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1611.06878.pdf">SANet</a><b></td>
      <td><sub>-/(0.692/0.928)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.616/0.837<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td rowspan="5"><b>Others<b></td>
      <td><b><a href="https://arxiv.org/pdf/1606.09549.pdf">SiamFC</a><b></td>
      <td><sub>(0.612/-)/()<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub><sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1605.05863.pdf">SINT</a><b></td>
      <td><sub>(0.655/0.882)/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <!-- <tr>
      <td><b><a href="http://davheld.github.io/GOTURN/GOTURN.pdf">GOTURN</a><b></td>
      <td><sub>-/(0.695/)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>0.636/0.751/0.515<sub></td>
      <td><sub>0.740/0.688<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.609/0.143/0.462<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>0.635/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr> -->
   <tr>
      <td><b><a href="https://www.cvl.isy.liu.se/research/objrec/visualtracking/conttrack/C-COT_ECCV16.pdf">CCOT</a><b></td>
      <td><sub>-/(0.682/0.824)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>0.581/-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Nam_Learning_Multi-Domain_Convolutional_CVPR_2016_paper.pdf">MDNET</a><b></td>
      <td><sub>-/(0.678/0.909)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   <tr>
      <td><b><a href="https://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Danelljan_Learning_Spatially_Regularized_ICCV_2015_paper.pdf">SRDCF</a><b></td>
      <td><sub>(0.633/-)/(0.605/)<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
      <td><sub>-<sub></td>
   </tr>
   
</table></font>

<!-- #### Contents
- [Single Objetc Tracking]() -->


- **Multiple Objects Tracking (MOT)**  
   - Download Papers (.zip) in [MOT20 (ECCV20, CVPR20, AAI20, ICML20, IJCAI20)](https://drive.google.com/drive/folders/1d0nRzwtsw1_QfdI-FxhSr1Ugp8fByHYZ?usp=sharing),
   [MOT19 (ICCV19, CVPR19, CVPRW9, AAI19, IV19)](https://drive.google.com/drive/folders/1b-c0LvIUQiEanvEg97GiZfVfVIEjcZSb?usp=sharing),
   [Others]()
  
   - <b><i>Bold italic</i></b> indicates online methods and non-bold indicates offline methods. * indicates MOT methods under the “private detector” protocol.
<table class="center">
   </font>
<font size="1" face="Courier New" >
   <tr>
      <td rowspan="2";><b>Conf.<b></td>
      <td rowspan="2"><b>Trackers<b></td>
      <td><b>MOT15<b></td>
      <td><b>MOT16<b></td>
      <td><b>MOT17<b></td>
      <td><b>MOT20<b></td>
      <td><b>KITTI<b></td>
      <td><b>UA-DETRAC<b></td>
      <td><b>BDD100K<b></td>
      <td><b>Waymo<b></td>
   </tr>
   <tr>
      <td><font size="1"> <b><sup>MOTA/IDF1<sup><b></td>
      <td><font size="1"> <b><sup>MOTA/IDF1<sup><b></td>
      <td><font size="1"> <b><sup>MOTA/IDF1<sup><b></td>
      <td><font size="1"> <b><sup>MOTA/IDF1<sup><b></td>
      <td><font size="1"> <b><sup>MOTA/MOTP<sup><b></td>
      <td><font size="1"> <b><sup>PR-MOTA<sup><b></td>
      <td><font size="1"> <b><sup>MOTA/MOTP<sup><b></td>
      <td><font size="1"> <b><sup>MOTA<sup><b></td>
   </tr>
   <tr>
      <td rowspan="4"><b>ECCV20<b></td>
      <td><b><a href="https://arxiv.org/pdf/2007.14557v1.pdf">CTracker</a><b></td>
      <td>-</td>
      <td><sub><b><i>67.6/57.2（*）</i></b><sub></td>
      <td><sub><b><i>66.6/57.4（*）</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1909.12605.pdf">JDE</a><b></td>
      <td>-</td>
      <td><sub><b><i>64.4/55.8（*）</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2004.01177.pdf">CenterTrack</a><b></td>
      <td>-</td>
      <td>-</td>
      <td><sub><b><i>61.5/59.6
       67.8/64.7（*）</i></b><sub></td>
      <td>-</td>
      <td><sub><b><i>89.44/85.0（*）</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123690613.pdf">DMM-NET</a><b></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub><b><i>12.2</i></b><sub></td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="8"><b>CVPR20<b></td>
      <td><b><a href="https://arxiv.org/pdf/1906.06618v2.pdf">DeepMOT</a><b></td>
      <td>-</td>
      <td><sub>54.8/53.4<sub></td>
      <td><sub>53.7/53.8<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr> 
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1912.07515.pdf">MPNTrack</a><b></td>
      <td><sub>51.5/58.6<sub></td>
      <td><sub>58.6/61.7<sub></td>
      <td><sub>58.8/61.7<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>    
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2006.07327.pdf">GNN3DMOT</a><b></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub>82.24/84.05<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr> 
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2003.11291.pdf">UMA</a><b></td>
      <td>-</td>
      <td><sub><b><i>50.5/52.8</i></b><sub></td>
      <td><sub><b><i>53.1/54.4</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1912.02096.pdf">MOTSNet</a><b></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub><b><i>58.2/84.0（*）</i></b><sub></td>
      <td>-</td>
   </tr>     
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2004.07472v1.pdf">SQE</a><b></td>
      <td>-</td>
      <td><sub>-/68.3<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr> 
   <tr>
      <td><b><a href="https://arxiv.org/pdf/2003.13870.pdf">RetinaTrack</a><b></td>
      <td>-</td>
      <td>-</td>
      <td><sub><b><i>39.19/-（*）</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub><b><i>44.92（*）</i></b><sub></td>
   </tr> 
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Pang_TubeTK_Adopting_Tubes_to_Track_Multi-Object_in_a_One-Step_Training_CVPR_2020_paper.pdf">TubeTK</a><b></td>
      <td>-</td>
      <td><sub><b><i>64.0/59.4（*）</i></b><sub></td>
      <td><sub><b><i>63.0/58.6（*）</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>     
   <tr>
      <td rowspan="1"><b>AAAI20<b></td>
      <td><b><a href="https://aaai.org/ojs/index.php/AAAI/article/view/6694/6548">DASOT</a><b></td>
      <td>-</td>
      <td><sub><b><i>46.1/49.4</i></b><sub></td>
      <td><sub><b><i>48.0/51.3</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr> 
   <tr>
      <td rowspan="1"><b>ICML20<b></td>
      <td><b><a href="https://arxiv.org/pdf/2006.14550.pdf">Lif_T</a><b></td>
      <td><sub>52.5/60.0<sub></td>
      <td><sub>61.3/64.7<sub></td>
      <td><sub>60.5/65.6<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>   
   <tr>
      <td rowspan="1"><b>IJCAI20<b></td>
      <td><b><a href="https://www.ijcai.org/Proceedings/2020/0074.pdf">GSM_Trackor</a><b></td>
      <td>-</td>
      <td><sub><b><i>57.0/58.2</i></b><sub></td>
      <td><sub><b><i>56.4/57.8</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="5"><b>ICCV19<b></td>
      <td><b><a href="https://arxiv.org/pdf/1903.05625.pdf">Tracktor++</a><b></td>
      <td><sub><b><i>44.1/46.7（*）</i></b><sub></td>
      <td><sub><b><i>54.4/52.5（*）</i></b><sub></td>
      <td><sub><b><i>53.5/52.3（*）</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1904.11489.pdf">STRN</a><b></td>
      <td><sub><b><i>38.1/46.6</i></b><sub></td>
      <td><sub><b><i>48.5/53.9</i></b><sub></td>
      <td><sub><b><i>50.9/56.5</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://openaccess.thecvf.com/content_ICCV_2019/papers/Chu_FAMNet_Joint_Learning_of_Feature_Affinity_and_Multi-Dimensional_Assignment_for_ICCV_2019_paper.pdf">FAMNet</a><b></td>
      <td><sub><b><i>40.6/41.4</i></b><sub></td>
      <td>-</td>
      <td><sub><b><i>52.0/48.7</i></b><sub></td>
      <td>-</td>
      <td><sub><b><i>77.1/78.8</i></b><sub></td>
      <td><sub><b><i>19.8（*）</i></b><sub></td>
      <td>-</td>
      <td>-</td>
   </tr> 
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1909.03850.pdf">mmMOT</a><b></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub><b><i>84.77/85.21</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td><b><a href="https://arxiv.org/pdf/1811.10742.pdf">3DT</a><b></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub><b><i>84.52/85.64</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1"><b>CVPR19<b></td>
      <td><b><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8954391">SAS</a><b></td>
      <td><sub>22.2/27.1<sub></td>
      <td>-</td>
      <td><sub>44.2/57.2<sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1"><b>CVPRW19<b></td>
      <td><b><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9025639">JBNOT</a><b></td>
      <td>-</td>
      <td>-</td>
      <td><sub><b><i>52.6/50.8</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1"><b>AAAI19<b></td>
      <td><b><a href="https://arxiv.org/pdf/1812.03621.pdf">LNUH</a><b></td>
      <td>-</td>
      <td><sub><b><i>47.5/43.6</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
   <tr>
      <td rowspan="1"><b>IV19<b></td>
      <td><b><a href="https://arxiv.org/pdf/1905.02843.pdf">FANTrack</a><b></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td><sub><b><i>77.72/82.32</i></b><sub></td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
   </tr>
</table></font>

<!-- #### Contents
- [Multiple Objects Tracking]() -->
       
### Contributors
- [Zhipeng Zhang](http://zhipengzhang.cn/)
- [Kaiwen Liu]()
- [Weiming Bai]()
- [Chao Liang]()