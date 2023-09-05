- 👋 Hi, I’m @muthuraman2002
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
muthuraman2002/muthuraman2002 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
class shopingcart:
    main_dict={"apple":100,"orange":50,"grapes":60,"mango":70,"guvi":150}
    product={}
    total=0
    def order(self):
        select_item=input("Enter thee product Name : ")
        if select_item=="apple":
            x.product["apple"]=100
            x.total+=100
            x.order()
        elif select_item=="orange":
            x.product["orange"]=50
            x.total+=50
            x.order()
        elif select_item=="grapes":
            x.product[select_item]=60
            x.total+=60
            x.order()
        elif select_item=="mango":
            x.product[select_item]=70
            x.total+= 70
            x.order()
        elif select_item=="guvi":
            x.product[select_item]=150
            x.total+=150
            x.order()
        else:
            print("Shopping Cart".center(30,"*"))

x=shopingcart()
print("Welcome To Shopping Cart".center(50,"*"))
for i,j in x.main_dict.items():
    print(i,"              ",j)
print(x.order())
for i,j in x.product.items():
    print(i,"              ",j)
print("Total             = ",x.total)
