多项比较 - multi-item-compare
-----------------------------------
指多个类的项目的若干个参数进行对比


结构说明
-----------------------------------
multi-item-compare
    title:string 
    valueDescription: array of ValueDescriptionItem
    data: array of DataItem

ValueDescriptionItem:
    title:string [opt]
    unit:string [opt]

DataItem:
    title:string
    value: array of number


其他说明
-----------------------------------
* valueDescription数组的长度必须和DataItem中value数组长度一致,关系一一对应