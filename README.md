# geo
x<-c(6,8,9,10,50,16)
x<-scan()
n<-length(x)
n<-scan()
k=1
for(i in 1:n)
{
  k=k*x[i]
}
gm=(k)^(1/n)
print("geometric mean")
print(gm)
print("gm using built in function")
print(exp(mean(logx)))

