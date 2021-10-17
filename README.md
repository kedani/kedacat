# README


# apple_price という変数に数値 200 を代入してください
apple_price = 200

# count という変数に数値 5 を代入してください
count = 5

# total_price という変数に、 apple_price と count を掛けたものを代入してください
total_price = apple_price * count

# 「 購入するりんごの個数は○○個です 」となるように出力してください
print('購入するりんごの個数は' + str(count) + '個です')

# 「 支払い金額は○○円です 」となるように出力してください
print('支払い金額は' + str(total_price) + '円です')

apple_price = 200

# input を用いて入力を受け取り、変数 input_count に代入してください
input_count = input('購入するりんごの個数を入力してください:')

# input_count を数値として代入してください
count = int(input_count)
total_price = apple_price * count

print('購入するりんごの個数は' + str(count) + '個です')
print('支払い金額は' + str(total_price) + '円です')

apple_price = 200
# 変数 money に数値 1000 を代入してください
money = 1000

input_count = input('購入するりんごの個数を入力してください：')
count = int(input_count)
total_price = apple_price * count

print('購入するりんごの個数は' + str(count) + '個です')
print('支払い金額は' + str(total_price) + '円です')

# money と total_price の比較結果によって条件を分岐してください
if money > total_price:
    print('りんごを' +str(count) + '個買いました')
    print('残金は'+str(money - total_price)+'円です')
elif money == total_price:
    print('りんごを'+str(count)+'個買いました')
    print('財布が空になりました')
else:
    print('お金が足りません')
    print('りんごを買えませんでした')




    # 関数 print_hand を定義してください
def print_hand():
    print('グーを出しました')

# 関数 print_hand を呼び出してください
print_hand()

# apple_price という変数に数値 200 を代入してください
apple_price = 200

# count という変数に数値 5 を代入してください
count = 5