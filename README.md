<meta name="google-site-verification" content="8lqQnvTSdV4_uwIRdsyMsUH5o8IQsNrRKDJpOWWtBBc" />

# MASTTA: A Multi-modal Architecture with Spatio-Temporal-Text Adaptation for Video-based Traffic Accident Anticipation
This is an official repo implementation of [A Multi-modal Architecture with Spatio-Temporal-Text Adaptation for Video-based Traffic Accident Anticipation](https://ieeexplore.ieee.org/abstract/document/10933925), IEEE Transactions on Circuits and Systems for Video Technology

The code and pre-trained weights will be released soon...

## Architecture
![image](https://github.com/user-attachments/assets/3bf7a73b-08c5-4e54-925e-d203767a57d5)


## Visualisation of Accident Events
![image](https://github.com/user-attachments/assets/49df8b29-e2ec-4184-80ba-f23a9933bf25)

## Results 
**Performance comparison of the achievable longest mTTA and the corresponding mAP of state-of-the-art models on the DAD and CCD datasets.**  
*The best balanced results are in bold.*
<table>
<tr>
<td valign="top">

<b>DAD Dataset</b>  

<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Source</th>
      <th>mAP (%)</th>
      <th>mTTA (s)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>DSA</td><td>ACCV16</td><td>48.4</td><td>1.34</td></tr>
    <tr><td>adaLEA</td><td>CVPR18</td><td>52.3</td><td>3.43</td></tr>
    <tr><td>GCRNN</td><td>ACMMM20</td><td>53.7</td><td>3.53</td></tr>
    <tr><td>FA</td><td>ICPR21</td><td>49.8</td><td>3.76</td></tr>
    <tr><td>DRIVE</td><td>ICCV21</td><td>62.8</td><td>2.78</td></tr>
    <tr><td>L-RA</td><td>CVPR21</td><td>49.1</td><td>3.04</td></tr>
    <tr><td>DSTA</td><td>TITS22</td><td>56.1</td><td>3.66</td></tr>
    <tr><td>GSC</td><td>TIV23</td><td>60.4</td><td>2.55</td></tr>
    <tr><td>DAA-GNN</td><td>PR23</td><td>70.6</td><td>1.59</td></tr>
    <tr><td>-</td><td>ICIP24</td><td>61.1</td><td>4.06</td></tr>
    <tr><td><b>MASTTA (Ours)</b></td><td>-</td><td><b>70.2</b></td><td><b>3.96</b></td></tr>
  </tbody>
</table>

</td>
<td style="width: 30px;"></td>
<td valign="top">

<b>CCD Dataset</b>  

<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Source</th>
      <th>mAP (%)</th>
      <th>mTTA (s)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>DSA</td><td>ACCV16</td><td>99.6</td><td>4.87</td></tr>
    <tr><td>GCRNN</td><td>ACMMM20</td><td>99.5</td><td>4.74</td></tr>
    <tr><td>DSTA</td><td>TITS22</td><td>99.6</td><td>4.52</td></tr>
    <tr><td>-</td><td>ICIP24</td><td>99.3</td><td>4.97</td></tr>
    <tr><td><b>MASTTA (Ours)</b></td><td>-</td><td><b>99.9</b></td><td><b>4.95</b></td></tr>
  </tbody>
</table>

</td>
</tr>
</table>

---

**Performance comparison of the achievable highest mAP and the corresponding mTTA of state-of-the-art models on the DAD dataset.**  
*The best balanced results are in bold.*

| Method         | Source    | mAP (%) | mTTA (s) | TTA₈₀R |
|----------------|-----------|---------|----------|--------|
| GCRNN          | ACMMM20   | 72.23   | 1.33     | 1.56   |
| L-RAI          | CVPR21    | 51.40   | 3.01     | -      |
| MViTv2         | CVPR21    | 64.49   | -        | -      |
| DSTA           | TITS22    | 72.34   | 1.50     | 1.81   |
| VideoSwin      | CVPR22    | 65.45   | -        | -      |
| UniFormer V2   | ICCV23    | 65.24   | -        | -      |
| DAA-GNN        | PR23      | 75.20   | 1.47     | -      |
| -              | ICIP24    | 75.61   | 3.31     | -      |
| **MASTTA (Ours)** | -       | **80.81** | **3.32** | **3.51** |

## Citation
If you find our work useful, plase use the following BiBtex for citation:

```bibtex
@ARTICLE{10933925,
  author={Patera, Patrik and Chen, Yie-Tarng and Fang, Wen-Hsien},
  journal={IEEE Transactions on Circuits and Systems for Video Technology}, 
  title={A Multi-modal Architecture with Spatio-Temporal-Text Adaptation for Video-based Traffic Accident Anticipation}, 
  year={2025},
  volume={},
  number={},
  pages={1-1},
  keywords={Visualization;Accidents;Adaptation models;Feature extraction;Attention mechanisms;Accuracy;Tuning;Data models;Computational modeling;Vehicle dynamics;accident anticipation;multi-modal architecture;parameter-efficient transfer learning;image-to-video adaptation},
  doi={10.1109/TCSVT.2025.3552895}
}



