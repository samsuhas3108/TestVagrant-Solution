import math
class ShopCart_Basket():
  def __init__(self,Product,Unit_Price_in_Rupees,GST_in_Per,Quantity):
    self.prod = Product
    self.Price= Unit_Price_in_Rupees
    self.GST = GST_in_Per
    self.Quantity = Quantity
    self.GST_in_rupee = (self.GST * self.Price)/100

    if(self.Price>500):
      self.Price = 5*(self.Price)/100
      self.GST_in_rupee = 5*(self.GST_in_rupee)/100

p1 = ShopCart_Basket("Leather wallet",1100,18,1)
p2 = ShopCart_Basket("Umbrella",900,12,4)
p3 = ShopCart_Basket("Cigarette",200,28,3)
p4 = ShopCart_Basket("Honey",100,0,2)

mpp = {}
mpp['p1'] = p1
mpp['p2'] = p2
mpp['p3'] = p3
mpp['p4'] = p4

maxi = float('-inf')

for key,value in mpp.items():
  if (mpp[key].GST)>maxi:
    maxi = mpp[key].GST
    product_name = mpp[key].prod
sum1 = 0
for key,value in mpp.items():
  sum1 += ((mpp[key].Price+mpp[key].GST_in_rupee)*mpp[key].Quantity)

print("",product_name)
print(sum1)








    


  

