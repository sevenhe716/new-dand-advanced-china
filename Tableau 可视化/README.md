# 说明文档

### 数据集来源

数据集来自Kaggle Rossmann Store Sales竞赛，由于项目的重心是EDA分析，所以已经做了部分数据清洗和特征工程，原始数据集可以从Kaggle上[下载](https://www.kaggle.com/c/rossmann-store-sales/data)。



### 数据集描述

* Store - a unique Id for each store  
* Sales - the turnover for any given day (this is what you are predicting)  
* Date - Date of the sales. extend to DayOfWeek, Year, Month, Day  
* Customers - the number of customers on a given day  
* StateHoliday - indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed on public holidays and weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None  
* SchoolHoliday - indicates if the (Store, Date) was affected by the closure of public schools  
* StoreType - differentiates between 4 different store models: a, b, c, d  
* Assortment - describes an assortment level: a = basic, b = extra, c = extended  
* CompetitionDistance - distance in meters to the nearest competitor store  
* CompetitionOpenDays - gives the time the nearest competitor was opened  
* Promo - indicates whether a store is running a promo on that day  
* Promo2 - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating  
* Promo2OpenDays - describes date when the store started participating in Promo2  
* PromoInterval - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store  



### 地理位置相关外部数据集来源

地理位置相关外部数据集来自https://www.kaggle.com/c/rossmann-store-sales/discussion/17048，由nicolas gaude通过Google Places API整理。



### 地理位置相关外部数据集描述

- placeid - 位置信息标识

- lat - 纬度latitude

- lon - 经度longitude

- opened_sunday - 周日是否营业 

- State - 州

- city - 城市

- elevation - 海拔

- population - 人口

- nearest_hotel - 最近的旅店距离

- nearest_railstation - 最近的火车站距离

- DayOfWeek - 星期信息

- OpenTime - 开始营业时间

- CloseTime - 结束营业时间

- OpenDuration - 营业时间


### 参考

原始数据集来自https://www.kaggle.com/c/rossmann-store-sales/data，已做部分数据清洗和特征工程

某些图的灵感来自https://www.kaggle.com/thie1e/exploratory-analysis-rossmann

地理信息外部数据集来自https://www.kaggle.com/c/rossmann-store-sales/discussion/17048