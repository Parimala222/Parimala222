- 👋 Hi, I’m @Parimala222
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Parimala222/Parimala222 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
x=[1,2,35,8,9,5,2,8,9,5,4,7]
l=[]
for i in x:
	if i not in l:
		p=x.count(i)
		if p==1:
			l.append(i)
print(l)
