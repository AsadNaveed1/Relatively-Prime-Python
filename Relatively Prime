# print(gcd(121,123))
x = input("Numbers: ")
inp= x.split()

checkPrp = True
checkMrp = True

for x in range(len(inp)):
        for i in range(x+1, len(inp)):
            y = int(inp[i])
            u = int(inp[x])
            while(y != 0):
                temp = u
                u = y
                y = temp%y
            gg = u
            if(gg > 1):
                checkPrp = False
if(checkPrp):
    print("prp")
else:
    gc = int(inp[0])
    for i in range(1, len(inp)):
        y = int(inp[i])
        x = gc
        while(y != 0):
            temp = x
            x = y
            y = temp%y
        gc = x
    if(gc > 1):
        checkMrp = False
    if(checkMrp):
        print("mrp")
    else:
        print("~")
