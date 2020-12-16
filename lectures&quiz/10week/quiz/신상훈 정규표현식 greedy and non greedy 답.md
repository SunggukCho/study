### 신상훈 정규표현식 greedy and non greedy 문제

- ide 쓰지 마시고 결과 값을 예측해 보세요

```python
import re

match = re.search('a.*c', 'a coke called a pig')
print(match.group())

text = '<html><head><title>Title</title>'

print(re.match('<.*t', text).span())
print(re.match('<.*t', text).group())

match = re.search('a .*', 'give anna a pen')
print(match.group())

match = re.search('cs.{1,10}', 'abcscsdcs')
print(match.group())

match = re.search('cs.{1,10}?', 'abcscsdcs')
print(match.group())
```

```python
'''
a coke c
(0, 29)
<html><head><title>Title</tit
a a pen
cscsdcs
csc
'''
```