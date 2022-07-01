# Reach Wisdom for Sale Tutorial
https://docs.reach.sh/tut/wfs/

Wisdom For Sale Bear Builder Project. As defined in the tutorial the "Wisdom for Sale" requirements are

1. Wisdom for Sale requires two participants, a Buyer and a Seller.
2. The buyer will need a pay function and a function that displays the wisdom.
3. The seller will need a function to input the wisdom, and to put it up for sale.
4. Both participants will be publishing information: the seller will publish the wisdom and the price, the buyer will publish their decision to purchase.
5. The buyer needs to be able to decide to NOT purchase the wisdom, so we need to create a function for cancelling the sale.
6. If the buyer does decide to buy the wisdom, then there needs to be a function that reports the payment to both the seller and the buyer.


```bash
~/reach/reach init

export REACH_CONNECTOR_MODE=ALGO
~/reach/reach run index buyer

```
