import sys
q = int(input().strip())
for a0 in range(q):
    n = int(input().strip())
    M = []
    for M_i in range(n):
       M_t = [int(M_temp) for M_temp in input().strip().split(' ')]
       M.append(M_t)
    sv=[]
    sh=[]
    for i in range(n):
        sv.append(0)
        sh.append(sum(M[i]))
        for j in range(n):
            sv[i]+=M[j][i]
    sv.sort()
    sh.sort()
    if sv==sh:
        print("Possible")
    else:
        print("Impossible")
