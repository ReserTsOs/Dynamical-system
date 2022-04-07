"""
Henon写像
h1(t+1) = 1 - a*h1(t)^2 + h2(t)
h2(t+1) = b*h1(t)

a, bはパラメータ
nは生成したいデータ数
"""

def Henon(a,b,n):
  
   h1 = np.zeros(n)
   h2 = np.zeros(n)
    
   h1[0] = 1.1
   h2[0] = 1.5
   for i in range(n-1):
       h2[i+1] = b*h1[i]
       h1[i+1] = 1 - a*(h1[i])**2 + h2[i]
        
   return h1
