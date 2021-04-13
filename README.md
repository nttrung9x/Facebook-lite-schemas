Facebook lite schemas

adb shell am start -a android.intent.action.VIEW -d "fblite://profile/UIDPROFILE " com.facebook.lite
adb shell am start -a android.intent.action.VIEW -d "fblite://page/UIDPAGE" com.facebook.lite ---> mở theo page của app, cái này chắc dành cho chạy nhiều clone  :))) mình đoán là vậy chứ chưa thử
adb shell am start -a android.intent.action.VIEW -d "https://www.facebook.com/groups/1777766135578951" com.facebook.lite
adb shell am start -a android.intent.action.VIEW -d "http://m.facebook.com/114578489989952/posts/446583693456095" com.facebook.lite
adb shell am start -a android.intent.action.VIEW -d "http://m.facebook.com/watch" com.facebook.lite
lệnh này thấy có bạn comment chạy gọn hơn
adb shell am start -a android.intent.action.VIEW fblite://profile/UIDPROFILE
adb shell am start -a android.intent.action.VIEW fblite://page/UIDPAGE
