# Gambling-Simulator-1

import random
item1 = ['🍇', '🍉', '🍎', '7']
item2 = ['🍇', '🍉', '🍎', '7']
item3 = ['🍇', '🍉', '🍎', '7']
ran_item1 = random.choice(item1)
ran_item2 = random.choice(item2)
ran_item3 = random.choice(item3)
coins = 0
mult = 1
if ran_item1 == '7'and ran_item2 == '7' and ran_item3 == '7':
    print(f'{ran_item1} | {ran_item2} | {ran_item3}')
    print('Jackpot!!')
else:
    print(f'{ran_item1} | {ran_item2} | {ran_item3}')
    print('Can\'t play slots without a lever vro🥀🥀')
