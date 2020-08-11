# 作業一 Gitrepo.
---
## 標題寫作(L2)
* 清單0～
* 清單1～
* 清單2～
* 清單3～

1. 標數字清單喔～
1. ~標數字清單喔～~
1. **標數字清單喔～**
1. *標數字清單喔～*
1. 標數字清單喔～
`有扣ㄟ`
---
* 多行code
```cpp
// add required headers according to your device
#include <SPI.h>
#include <Ethernet.h>
#include <ThingerEthernet.h>

// initialize Thinger instance (type can change depending on your device)
ThingerEthernet thing("username", "deviceId", "deviceCredential");

void setup() {
    // initialize your sensors and pins

    // initialize wifi (see examples for your device)

    // add resources here, like sensors, lights, etc.
}

void loop() {
  // call always the thing handle in the loop and avoid any delay here
  thing.handle(); 
  // here you can call endpoints
  // and also you can stream resources
}
```

> 該程式引用自先前專案
[在此處了解如何建立電子郵件端點。](https://gtrx8fd3ds.gitbook.io/thinger-io/console#email-endpoint)
![大麻的啦!](weed.jpg)
- [] 100g
- [x] 500g

---
## 標題二(L2)