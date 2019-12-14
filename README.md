# spatdata
List of publicly available spatiotemporal data sets (e.g., transportation data).



| No | Name | Intro. | Download |
|---:|:------|:--------|:---------|
|  1 | **PeMS-BAY** | This data set contains the speed information of 325 sensors in the Bay Area, USA lasting for six months ranging from January 1, 2017 to June 30, 2017. The total number of observed traffic data is 16,941,600 and the time interval is 5-minute. | [GitHub](https://github.com/liyaguang/DCRNN), [Google Drive](https://drive.google.com/open?id=10FOTa6HXPqX8Pf5WRoRwcFnW9BrNZEIX), [Baidu Yun](https://pan.baidu.com/s/14Yy9isAIZYdU__OYEQGa_g) |
|  2 | **Seattle Inductive Loop Detector Dataset** | The data is collected by the inductive loop detectors deployed on freeways in Seattle area. This data set contains spatiotemporal speed information of the freeway system within a whole year of 2015. The time interval of this data set is 5-minute. Here, Loop Adjacency Matrix describes the traffic network structure as a graph. Notably, the speed data is stored by a pickle file and can be loaded by `Pandas`: | [GitHub](https://github.com/zhiyongc/Seattle-Loop-Data), [Google Drive](https://drive.google.com/drive/folders/1XuK0fgI6lmSUzmToyDdHQy8CPunlm5yr?usp=sharing) |
```python
import pandas as pd
data = pd.pickle('../speed_matrix_2015')
```
| | | | |
|---:|:------|:--------|:---------|
|  3 | **Guangzhou Traffic Speed Dataset** | This data set contains the speed information of 214 anonymous road segments (mainly consist of urban expressways and arterials) in Guangzhou, China within two months (i.e., 61 days from August 1, 2016 to September 30, 2016) at 10-minute interval. | [Zenodo](https://zenodo.org/record/1205229) |
