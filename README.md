## RGBE-Tracking-Results-Datasets-and-Methods

**An investigation for RGBE tracking. 
Hopefully, it can help other researchers become familiar with multi-modal tracking as soon as possible.
This repository is started on 27/12/2023, and will keep on updating.**

-----
>This repository will give a detail investigation of the RGBE tracking community, including the Datasets, Results, and the Methods.
> 
>  - [x] Datasets
>  - [x] Results
>  - [x] Methods
>  -  ...
-----

## Survey Papers


## Datasets
***Real Data***

| Dataset | Publish  | GitHub| Introduction|
|--|--|--| --|
| CRSOT| Arxiv'2024 |[CRSOT](https://github.com/Event-AHU/Cross_Resolution_SOT) |CRSOT: Cross-Resolution Object Tracking using Unaligned Frame and Event Cameras|
| FELT| Arxiv'2024 |[FELT](https://github.com/Event-AHU/FELT_SOT_Benchmark) |Long-term Frame-Event Visual Tracking: Benchmark Dataset and Baseline|
| COESOT| Arxiv'2022 | [COESOT](https://github.com/Event-AHU/COESOT)|Revisiting Color-Event based Tracking: A Unified Network, Dataset, and Metric|
| VisEvent| TCYB'2023 |[VisEvent](https://github.com/wangxiao5791509/VisEvent_SOT_Benchmark?tab=readme-ov-file)|VisEvent: Reliable Object Tracking via Collaboration of Frame and Event Flows|
| FE108/FE240hz| ICCV'2021 | [FE108/FE240hz](https://github.com/Jee-King/ICCV2021_Event_Frame_Tracking)|Object Tracking by Jointly Exploiting Frame and Event Domain|
-----

## Results


<table>
    <tr> 
        <th colspan="1"></th> 
	      <th colspan="1"></th> 
	      <th colspan="1"></th> 
        <th colspan="2">FE108</th> 
        <th colspan="2">VisEvent</th> 
        <th colspan="2">FELT</th>
    </tr>
    <tr>
    	<td> Methods</td>
    	<td>Venue</td>
	    <td>Speed</td>
    	<td> PR</td>
    	<td> SR</td>
    	<td> PR</td>
   	  <td> SR</td>
    	<td> PR</td>
    	<td> SR</td>
    </tr>
    <tr>
    	<td> eMoE-Tracker</td>
    	<td>Arxiv'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 76.4</td>
   	<td> 61.3</td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> OneTrack</td>
    	<td>CVPR'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 76.7</td>
   	<td> 60.8</td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> UnTrack</td>
    	<td>CVPR'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 76.3</td>
   	<td> 59.7</td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> SDSTrack</td>
    	<td>CVPR'2024</td>
	<td>20.86</td>
    	<td> </td>
    	<td> </td>
    	<td> 76.7</td>
   	<td> 59.7</td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> XTrack</td>
    	<td>Arxiv'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 75.6</td>
   	<td> 59.1</td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> KSTrack</td>
    	<td>TCSVT'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 70.3</td>
   	<td> 57.2</td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> SeqTrackv2</td>
    	<td>Arxiv'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 80.0</td>
   	<td> 63.4</td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> MINet</td>
    	<td>IVC'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 74.1</td>
   	<td> 59.4</td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> AMTTrack</td>
    	<td>Arxiv'2024</td>
	<td>61</td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> </td>
    	<td> 57.2</td>
    	<td> 45.5</td>
    </tr>
    <tr>
    	<td> Mamba-FETrack</td>
    	<td>PRCV'2024</td>
	<td>24</td>
    	<td> 91.0</td>
    	<td> 58.7</td>
    	<td> </td>
   	<td> </td>
    	<td> 55.6</td>
    	<td> 43.5</td>
    </tr>
    <tr>
    	<td> MMHT</td>
    	<td>Arxiv'2024</td>
	<td>21</td>
    	<td> 93.6</td>
    	<td> 63.0</td>
    	<td> 73.3</td>
   	<td> 55.1</td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> TENet</td>
    	<td>Arxiv'2024</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 76.5</td>
   	<td> 60.1</td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> HRCEUTrack</td>
    	<td>ICCV'2023</td>
	<td></td>
    	<td> 96.2</td>
    	<td> 68.5</td>
    	<td> </td>
   	<td> </td>
    	<td> 56.4</td>
    	<td> 44.8</td>
    </tr>
    <tr>
    	<td> AFNet</td>
    	<td>CVPR'2023</td>
	<td>36.21</td>
    	<td> 87.0</td>
    	<td> 58.4</td>
    	<td> 59.3</td>
   	<td> 44.5</td>
    	<td> 36.6</td>
    	<td> 28.9</td>
    </tr>
    <tr>
    	<td> CEUTrack</td>
    	<td>Arxiv'2023</td>
	<td>75</td>
    	<td> 84.5</td>
    	<td> 55.6</td>
    	<td> 69.1</td>
   	<td> 53.1</td>
    	<td> 56.4</td>
    	<td> 44.9</td>
    </tr>
    <tr>
    	<td> ViPT</td>
    	<td>CVPR'2023</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 75.8</td>
   	<td> 59.2</td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> ProTrack</td>
    	<td>ACMMM'2022</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> 61.7</td>
   	<td> 47.4</td>
    	<td> </td>
    	<td> </td>
    </tr>
</table>

<table>
    <tr> 
        <th colspan="1"></th> 
        <th colspan="1"></th> 
	    <th colspan="1"></th> 
        <th colspan="3">COESOT</th> 
        <th colspan="3">CRSOT</th> 
    </tr>
    <tr>
    	<td> Methods</td>
    	<td>Venue</td>
	<td>Speed</td>
    	<td> PR</td>
    	<td> NPR</td>
    	<td> SR</td>
    	<td> PR</td>
    	<td> NPR</td>
    	<td> SR</td>
    </tr>
    <tr>
    	<td> eMoE-Tracker</td>
    	<td>Arxiv'2024</td>
	<td></td>
    	<td> 79.9</td>
    	<td> 82.3</td>
    	<td> 67.1</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> MMHT</td>
    	<td>Arxiv'2024</td>
	<td>21</td>
    	<td> 74.0</td>
    	<td> </td>
    	<td> 65.8</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> TENet</td>
    	<td>Arxiv'2024</td>
	<td></td>
    	<td> 76.8</td>
    	<td> 75.3</td>
    	<td> 68.4</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> HRCEUTrack</td>
    	<td>ICCV'2023</td>
	<td></td>
    	<td> 73.8</td>
    	<td> 71.9</td>
    	<td> 65.0</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> CEUTrack</td>
    	<td>Arxiv'2023</td>
	<td>75</td>
    	<td> 76.0</td>
    	<td> 74.9</td>
    	<td> 62.7</td>
   	<td> </td>
    	<td> </td>
    	<td> </td>
    </tr>
    <tr>
    	<td> ViPT</td>
    	<td>CVPR'2023</td>
	<td></td>
    	<td> </td>
    	<td> </td>
    	<td> </td>
   	<td> 66.0</td>
    	<td> 64.9</td>
    	<td> 54.6</td>
    </tr>
   </table>

-----
## Contributors
- [Zhangyong Tang](https://github.com/Zhangyong_Tang)
- [PRCI-Lab](https://github.com/PRCI-Lab)

**Questions**

If you have any questions, please contact zhangyong_tang_jnu@163.com, and wechat: Tzy18861871359 is also welcomed.



 
