whatif = "The World ends today"
print(len(whatif) - len("not at all"))


m = ["Dune", "Jaws", "VP", "Titanic", "Ratatouille"]
print(m[-2][3] + m[-1][-1] + m[-1][-4] + m[4][-6] + m[-5][1])



strenght = {"IT": 70, "ECE": 65, "EEE": 75, "AIML": 50}
strenght.update({"CSE": 64})
print(strenght)

event = 'Easter at April 20'
l = event.split(" ")
print("#".join(l[::-2]))

name = "college of Enginerring"
print(name[8:11] + "cyc" + name[3] + name[-3:])

print(float(5+int(4.39+2.1)%2))

print(3*1**3)

p,q=8,3
p,q,p=p+1,q+5,p+10


print(16//3+3**3+15/4-9)


t=(2,4,(6,8,(10,12)),14)
print(t[2][2][0]*t[0]+t[-1])
