# sun_2024
Solar Observation Report in 2024

## 1. Gathering data
- 48 data collected from September 10, 2024 to February 13, 2025

![Solar_obs_copper](image/Solar_obs_copper.png)

## 2. Analysis with python & python packages

- astropy, opencv, skimage, etc
<img src="image/Sun_ex.png" width="500" height="500">


## 3. Sunspots detecting and comparing

- Comparing the results of the morphology, Canny Edge detector, STARA and ASSA
  + (morphology, Edge detector) Using functions provided by skimage, opencv package
  + (STARA) Using functions provided by the sunpy package
  + (ASSA) Refer to the results on the webpage `https://spaceweather.kasa.go.kr/flare.do`

![canny_edge](image/ex_edges_detected.png)

![STARA](image/ex_hmi_map.png)

![ASSA](image/ex_2024_10_11.png)
