體重=float(input('請輸入您的體重（公斤）：'))
身高=float(input('請輸入您的身高（公分）：'))

BMI=體重/(身高/100)**2
print('您的BMI值為:',BMI)

if BMI<18.5:
    print('您的體重過輕')
elif 18.5<=BMI<24:
    print('健康體位')
else:
    print('體位異常')
    if 24<=BMI<27:
       print('過重')
    elif 27<=BMI<30:
       print('輕度肥胖')
    elif 30<=BMI<35:
       print('中度肥胖')
    else:
       print('重度肥胖')
