print("   🎲TAI XIU B52🎲")
a=int(input("nhap so tien cuoc:"))
c=input("tai hay xiu:")
s=""
import random
b=random.uniform(3,18)
if b>=3 and b<=10 :
    s="xiu"
else:
    s="tai"
if c==s:
    print("ket qua","💵🎲",s,"🎲💵")
    print("ban da win",a*2,"💳💵💲")
else:
    print("ket qua","💵🎲",s,"🎲💵")
    print("ban da thua",a,"💳💵💲")
