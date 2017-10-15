# ChinaID

> Verify the Chinese identity card number and obtain the information from it.

## 1. Install

```shell
pip install ChinaID
```

## 2. Import

```python
import ChinaID
```

## 3. Usage

```python
ChinaID.parse('440104197001017010')
# result = {
#     'CensusRegister': {
#         'Province': '广东省',
#         'City'    : '广州市',
#         'Region'  : '越秀区'
#     },
#     'Birthday': '19700101',
#     'Gender'  : '男',
#     'Legal'   : Ture
# }
```

## 4. Update area number

```py
ChinaID.update_area_number()
```

## 5. Information source 

[中华人民共和国国家统计局>>行政区划代码](http://www.stats.gov.cn/tjsj/tjbz/xzqhdm/)