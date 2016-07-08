# GetPhoneModel
判断手机的型号，iPhone，iPad，iPod Touch,方便适配


# How to use

将工程中的WSGetPhoneTypeController.h和WSGetPhoneTypeController.m拖放在你将要使用的工程下面即可。
类方法+ (NSString*)getPhoneModel获取手机型号。不用创建对象：
NSString *phoneModelStr = [WSGetPhoneTypeController getPhoneModel];

