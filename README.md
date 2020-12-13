# pppp001 version 0.1

### วิธีติดตั้ง

เปิด CMD / Terminal

```python
pip install pppp001
```

### how to 

เปิด IDLE ขึ้นมาแล้วพิมพ์...

```python
from pppp001 import Student, SpecialStudent

print('===1 jan===')
student0 = SpecialStudent('Mark Zuckerberg','Bill Gates')
student0.AskEXP()
student0.ShowEXP()

student1 = Student('Albert')
print(student1.name)
student1.Hello()

print('--------------------')
student2 = Student('Steve')
print(student2.name)
student2.Hello()

print('===2 jan===')
student1.AddEXP(20)
print(student1.name,student1.exp)
print(student2.name,student2.exp)

for i in range(5):
	student2.Coding()

student1.ShowEXP()	
student2.ShowEXP()		
```

pppp001 version 0.1