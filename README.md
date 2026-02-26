import random

answer = random.randint(1, 100)
guess = 0

while guess != answer:
    guess = int(input("請輸入數字："))
    
    if guess > answer:
        print("太大了")
    elif guess < answer:
        print("太小了")
    else:
        print("猜對了！")
