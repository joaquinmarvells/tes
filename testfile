inp1 = input().split()
n = int(inp1[0])
m = int(inp1[1])
x = int(inp1[2])
matrix1 = []
hasilmatrix = [[0]*m for _ in range(n)]
for k in range(n):
    temp = []
    inp3 = input().split()
    for l in range(x):
        temp.append(int(inp3[l]))
    matrix1.append(temp)

matrix2 = []

for o in range(x):
    temp = []
    inp3 = input().split()
    for p in range(m):
        temp.append(int(inp3[p]))
    matrix2.append(temp)

for f in range(n):
    for g in range(x):
        for h in range(m):
            hasilmatrix[f][h] += matrix1[f][g] * matrix2[g][h]

for row in hasilmatrix:
    print(*row)