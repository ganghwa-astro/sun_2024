# sun_2024
Solar Observation Report in 2024

Report folder `report_github > (250306) 24년도 종합관측보고서_1부_깃허브.pdf`

## 1. Data gathering
- 48 data collected from September 10, 2024 to February 13, 2025

![Solar_obs_copper](image/Solar_obs_copper.png)

## 2. Analyzing with python & python packages

- astropy, opencv, skimage, etc.
<img src="image/Sun_ex.png" width="500" height="500">


## 3. Detecting and comparing sunspots

- Comparing the results of the morphology, Canny Edge detector, STARA and ASSA
  + **(morphology, Edge detector)** Using functions provided by skimage, opencv package
  + **(STARA)** Using functions provided by the sunpy package
  + **(ASSA)** Refer to the results on the webpage `https://spaceweather.kasa.go.kr/flare.do`

<img src="image/ex_edges_detected.png" width="500" height="350">
<img src="image/ex_hmi_map.png" width="500" height="400">


## 4. Visualizing the trends of sunspots

- Time Series with LOWESS smoothing of sunspots

![ts_viz](image/time_series_with_LOWESS.png)



## 5. Summarizing and Reporting

![abstract](image/process.png)
