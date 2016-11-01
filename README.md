# OOAD-WEEK10
Sequence Diagram
ภาพที่1  Enrolling in a seminar (method)
```
@startuml
state "astudent student" as astudentstudent
astudentstudent-->seminar:enrollstudent
seminer-->Course:isStudentEligilble
Course-->astudentstudent:getseminarHistory
astudentstudent-->Course:serninarHistory
seminer-->astudentstudent:enrollmentStatus
@enduml
```
![](http://www.plantuml.com/plantuml/img/RKz12iCm3Bld5Q7tVY27KHY3tlk2Z9fYS1AmdKD_FxEaT8ITP4j2iXVHo5eJEHiK_1H5wmvPVSV9H_4NsS4D-pm_11Bco04o5wBBzsM1JN-MoW81PMlIY_10UXEuffXb20q7Q4zTKRJm-QUsnmfm_ZNUlMDeko_PkDc_LTm2URVtFm00)

ภาพที่2
```
@startuml
autonumber
user ->somsri : Authentication Request
user <- somsri : Authentication Response
@enduml
```
![](http://www.plantuml.com/plantuml/img/TStB2O0m40N0UwhO1jA0YCGMx23g0mDcL_VJlu9dxmDJpAjwz3FLSE7eApI5GIbF9jsqqK1p-07sjbLlmhJW3fX_RCpqx-mIDgG2tj_Y0G00)

ภาพที่ 3
```
@startuml

title checkmail 
start
:Computer;
:Sever;
@enduml
```
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuUBYAiaioKbLICv8JSxEJSpCKU02ot5PEUVd5fIMf1PPSra5fvQ1Q2ukXzIy5A0k0000)


ภาพที่ 4
```
customer -> Waiter : order
Waiter --> customer : serve wine
Waiter --> customer : serve food
customer -> Waiter : pay
Waiter -> chef : order food
chef --> Waiter : pickup
```
![](http://www.plantuml.com/plantuml/img/IoujBidFJIrIqBLJ24_CB06oh1JoYr9IYxYWN5sWJ39CbPL2SMfHMQf2UMPUAbu5QVdvALp9s0mlIAo4wmHgp4XDWza8rGGIqKNHaPcSNLe00000)

ภาพที่ 5
```
@startuml
somchai->somchai: A Sequence diagram is an interaction diagram \nthat shows how objects operate \nwith one another and in what order. \nIt is a construct of a message sequence chart.
@enduml
```

![](http://www.plantuml.com/plantuml/img/FOux3i9034Jxd68kG0v0WQ2afgKnkoQxYDXWEyhrCGXe_D6Cns_OUv35Cjy7rxaqwflTTzZYW1C_5vR2g9qcendTGO8kmKObkifVEKiq2dZJrP45Uhbn2OS-qXkSXhL7WmfdX4PZorup2-lxKAsoZUawnkSBYeg7BIMbQwupkzF4y1zICbgCmvwb9luB)


README.md 

md เป็นภาษา Markdown นิยมใช้ใน wiki ของ github 

ตัวอย่างโค้ด
```
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3
 
```

ผลที่ได้
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3


## Code ภาษาซี

ตัวอย่างโค้ด
<pre>
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
</pre> 
ผลที่ได้
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
 
