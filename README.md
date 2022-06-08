import statistics as stat
l=[3,4,5]
print(stat.mean(l))
print(stat.geometric_mean(l))
print(stat.harmonic_mean(l))

l1=[3,80]
print(stat.harmonic_mean(l1))
l2=[4,70]
print(stat.harmonic_mean(l2))


import statistics as stat
l=[1,2,1,3,5,80,50,45,32,7,67,6,34,35,78]
print(stat.mean(l))
print(stat.quantiles(l))
print(stat.median(l))
l.sort()
l
len(l)

