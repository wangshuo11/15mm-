# 15mm-
之前matlab代码求出的降雨量15毫米过滤，面积8,过滤，以及轮廓数目10过滤，得到的雨区的Id，如果是20020103.10,由于字符串转换会把后面的0抹去，导致出现20020103.1,会导致数据库查询时雨区的id不唯一，这是修改后的代码,降雨量15毫米为例子
