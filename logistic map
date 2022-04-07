"""
logistic写像
x(t+1) = a * x(t) * ( 1-x(t) )
a：パラメータ
n；生成したいデータ数
"""

def logistic(a, n):
  
  x = np.zeros(n)

  #初期値の設定
  x[0] = 0.1
    
  for i in range(n-1):
    x[i+1] = a*x[i]*(1-x[i])
        
  return x
