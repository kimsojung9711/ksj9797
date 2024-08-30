def solution(n):
 answer = 0
 # 1부터 n까지의 숫자를 반복적으로 가져옵니다.
 for i in range(1, n+1):
 # 현재 숫자 i가 n의 약수인지 확인합니다.
 if n % i == 0:
 # 만약 i가 n의 약수라면, answer에 i를 더합니다.
 answer += i

 return answer
