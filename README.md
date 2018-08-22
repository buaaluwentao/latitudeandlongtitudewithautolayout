# latitudeandlongtitudewithautolayout
1. 自动布局时当前view的属性设置中toitem应设置为nil，multiplier设
置为1。

2. 使用自动布局的对象应取消autoresize。

3. view自身的属性（如宽高）应添加到自身，从兄弟参考来的属性应添加到父view，从父view参考来的属性应添加到父view。
