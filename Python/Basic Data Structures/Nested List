n = int(raw_input())
marks = [[raw_input(), float(raw_input())] for i in  xrange(n)]           
scores = sorted({s[1] for s in marks})
result = sorted(s[0] for s in marks if s[1] == scores[1])
print '\n'.join(result)
