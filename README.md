h=int(input("enter a hour in 24-formate:"))
m=int(input("enter a minute:"))
if h>=12:
    h=h-12
x=(h+(m/60))*30
y=m*6
angle=abs(x-y)
s_angle=min(angle,360-angle)
print("smallest angle between hours hand min hand",s_angle)
