def main():
    earth_weight = float(input("请输入你当前的体重（kg）: "))
    growth_rate = 0.5
    
    print("年份\t地球体重(kg)\t月球体重(kg)")
    print("-" * 35)
    
    for year in range(1, 11):
        earth_current = earth_weight + year * growth_rate
        moon_current = earth_current * 0.165
        print(f"{year}\t{earth_current:.1f}\t\t{moon_current:.2f}")

if __name__ == "__main__":
    main()[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/LtBGexu8)
### pythonAssignment_weightConvert2
### 月球上的重量是地球上的16.5%，假如你在地球上每年增长0.5kg，编写程序输出未来10年你在地球和月球上的体重变化。
### 把你的代码编写在main.py这个文件里
