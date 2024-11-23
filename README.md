# Christmas-gift-ideas
Get christmas gift ideas for both girls and guys!
with open('data christmas gifts girls', 'r') as file:
    girls_gifts = file.read()

with open('data christmas gifts guys', 'r') as file:
    guys_gifts = file.read()

while True:
    category = input('looking for christmas gifts or a girl or a guy?: ')
    if category == 'girl':
        print(girls_gifts)
        break
    elif category == 'guy':
        print(guys_gifts)
        break
    else:
        print('invalid answer, choose girl or guy!') 
