# Story 1

```txt
As a supermarket shopper,
So that I can pay for items at checkout,
I'd like to be able to know the total cost of items in my basket.
```

## Nouns && Verbs

### Nouns

- Supermarket
- Shopper
- Items
- Basket
- Cost

### Verbs

- Pay
- Checkout
- Know

| Methods | Inputs | Data | Scenario | Outputs
| ------ | ------ | ------ | ----- | -----
| priceTotal(shoppingCartList) | shoppingCartList(@Object[])| shoppingCartListItem = `{name: @String, id: @Number, price: @Number, quantity: @Number}` | Items in cart | sum of item quantity * item price
| | | | No items in cart | 0

# Story 2

```txt
As an organised individual,
So that I can evaluate my shopping habits,
I'd like to see a receipt that includes line items (quantity, name, cost) and the total cost.
```

## Nouns && Verbs

### Nouns

- Individual
- Shopping habits
- Receipt
- Items (quantity, name, cost)
- Total cost

### Verbs

- Evaluate
- See

| Methods | Inputs | Data | Scenario | Outputs
| ------ | ------ | ------ | ----- | -----
| displayReceipt(receiptList) | shoppingCartList(@Object[])| shoppingCartListItem = `{name: @String, id: @Number, price: @Number, quantity: @Number}` | Items in cart | sum of item quantity * item price
| | | | No items in cart | 0