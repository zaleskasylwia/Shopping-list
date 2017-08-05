# Shopping-list

#3 - Shopping list

Do you know Listonic? So make let's something similar.

# Classes:

## Item

A thing to buy.

### Attributes:

name

quantity

unit - quantity unit

price_per_unit

categories - list of categories that this item belongs to e.g: ["food", "vegetables"]

is_bought - is the item already bought

### Methods:

__str__()

__eq__()

get_total_price() - price * quantity

## ShoppingList

Used to aggregate shopping items

### Attributes:

name

date

items

### Methods:

get_items(is_bought) - returns list of bought or not bought items

get_total_price() - return total price of the shopping list

sort_by(attr) - sort items by quantity/price/name
