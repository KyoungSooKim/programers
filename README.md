# 프로그래머스 알고리즘 Reviews with python

## BFS/DFS
* queue : from collections import deque
* recursion : import sys sys.setrecursionlimit(10**8)
* 상하좌우 : dx = [-1, 0, 1, 0], dy = [0, 1, 0, -1]

## HASH
* dict[key] = dict.get(key,0) + 1
* dict = {} or dict = dict()
* b = dict(a) , copy.deepcopy(a)
* for key, val in dict.items()
* del dict[key]

## LIST
* deep copy : import copy, copy.deepcopy(list)
* 리스트 리버스 : list.reverse()
* '@'.join(list)  ex : a@b@c  

## SORT
 * list = sorted(list, key = lambda x : (x[0], -x[1]))

## STR
* for구문으로 string 다루기 : for X in "abc" => X = a, b, c
* rjust : "AB".rjust(5,'1') == "111AB"
* replace : "AB".replace('1', '#') == "###AB"

## FOR
 * for x, y in zip(list1, list2)
 * for i, v in enumerate(list)

## PERMUTATIONS/COMBINATIONS
* form itertools import combinations or permutations
* permutations(list, length) , combinations(list)
* list(set(map(''.join, permutations(list,length))))

## 기타
* 타입확인 : type()
* 10진수 2진수로 변환 : bin(x)[2:] (문자의 앞 2개는 ob라서 슬라이싱함)
* chr(90) = 'Z' , ord("Z") = 90
