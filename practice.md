# Matlab-Optimization: Penalty func
최적화를 통해 성능과 제약조건 사이에 이해득실

</br>### Constraints
The purpose of penalty function is to convert <span style="color:red">'Constrained Pronlem'</span> into <span style="color:orange">' unconstrained problem'</span> 
- 제약된 문제를 제약안된 문제로 바꾸기 위해 

ex) Toll freeway: ( 위반시 벌금 부과 )

1. speed limit 65mpg

1. over 65 will cost $50   

## 1 Initial steps 
constraints into the form] $$number \leq$$ 

ex) $$x\le5 \rarr x-5\le0$$ 
Minimize f(x) <span style = "color:red">add</span> : penalty 최대화
</BR>Maximize f(x) <span style = "color:red">subtract</SPAN> : penalty 최소화

## 2 Quadratic Loss(제곱 손실 함수)
