# MomentoAI-coding-test

1번 문제
```
def solution(arr):
    # 배열이 하나의 원소만 있는 경우 -1 반환
    if len(arr) == 1:
        return [-1]
    
    # 가장 작은 값
    min_value = min(arr)
    
    # 가장 작은 값을 제거한 배열 반환
    arr.remove(min_value)
    
    return arr
```

2번 문제
```
def solution(s):
    # sorted() 함수로 내림차순 정렬 후, 문자열로 반환
    return ''.join(sorted(s, reverse=True))
```
