# RUSLE tends to overestimate soil erosion in revegetated conditions: Evidence from long-term runoff plots monitoring on China’s Loess Plateau / RUSLE倾向于高估植被恢复条件下的土壤侵蚀：基于中国黄土高原长期径流坡面监测的证据

## Introduction 简介

This repository provides the data used in the Catena paper “RUSLE tends to overestimate soil erosion in revegetated conditions: Evidence from long-term runoff plots monitoring on China’s Loess Plateau”. The study evaluated hundreds of different RUSLE model configurations. The data come from long-term monitoring (2016–2023) of 10 runoff plots in a revegetated Fangta watershed on the Loess Plateau, China. The dataset includes records of rainfall events, observed soil loss per plot, simulated erosion rates, and model performance metrics (NSE, MAPE) over 2016–2023.
本仓库提供用于Liao等人（2025）研究的数据。该研究评估了144种不同的RUSLE模型配置。数据来源于中国黄土高原方塔流域10个径流坡面的长期监测（2016–2023年）。数据集包含2016–2023年期间的降雨记录、土壤流失观测值、模拟侵蚀速率和模型性能指标（NSE、MAPE）。

## Data Content 数据内容说明

* `rainfall_records.csv`: Contains the recorded rainfall events, including date/time, total precipitation (mm), rainfall duration (hours), and intensity (mm/h).
  降雨记录文件：包含每个降雨事件的数据，包括日期/时间、总降雨量（单位：毫米）、降雨持续时间（单位：小时）和降雨强度（单位：毫米/小时）。
* `soil_loss_observed.csv`: Lists the observed soil loss for each runoff plot and rainfall event (tons per hectare).
  土壤流失观测文件：列出了每个径流坡面在每次降雨事件中实测的土壤流失量（单位：吨/公顷）。
* `simulated_erosion_rates.csv`: Provides RUSLE-simulated soil loss for each plot/event under the 144 model configurations (tons per hectare).
  模拟侵蚀速率文件：提供了在144种RUSLE模型配置下，每个坡面和每次事件的模拟土壤流失量（单位：吨/公顷）。
* `performance_metrics.csv`: Contains model performance metrics for each RUSLE configuration and scale, including Nash–Sutcliffe Efficiency (NSE, dimensionless) and Mean Absolute Percentage Error (MAPE, %).
  模型性能指标文件：包含每种RUSLE配置在不同模拟尺度下的性能指标，包括NSE（纳什-舒特利夫效率，无量纲）和MAPE（平均绝对百分比误差，百分比）。

## Citation 引用要求

Please cite: (Liao and Wang et al., 2025), Liao#, J., Wang#, J., Jiao, J., Yan, Z., Li, J., Zhang, Z., Li, M., Xu, Q., Jiang, X., Zhao, W., Ling, Q., Sheng, H., Chen, Y., & Wu, T. (2025). RUSLE tends to overestimate soil erosion in revegetated conditions: Evidence from long-term runoff plots monitoring on China’s Loess Plateau. Catena, 258, 109285. https://doi.org/10.1016/j.catena.2025.109285
when using this data. Commercial use of the data is not allowed.
请在使用本数据时引用 Liao and Wang 等（2025）发表在Catena的论文。禁止商业使用。

## Contact 联系方式

For questions, contact: [wangjiaxi@nwafu.edu.cn](mailto:wangjiaxi@nwafu.edu.cn)
如有问题，请联系：[wangjiaxi@nwafu.edu.cn](mailto:wangjiaxi@nwafu.edu.cn)

## License 许可

This dataset is free for non-commercial academic use only. Please cite the reference above when using the data.
本数据仅限于非商业学术使用。使用本数据时请注明上述论文出处。

**References:** Liao et al. (2025) *Catena* 258:109285; data availability.
