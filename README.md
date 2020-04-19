# Let's Compare Banks in Bahrain!

This is an open source repository that helps you find the perfect credit card 💳 for you!
We collect cashback rates of different cards across Bahrain and make it easy for people to
search and find the right card for them.

This is open source, and we make no guarantees about the accuracy of this data. However, we
do require that any contribution to this repository is provided along with some proof of the
source of a certain rate

## Contributing

If your bank is missing, or if you spot a mistake, please [Edit the CSV](https://github.com/amal-ai/bahrain-banks/blob/master/data/credit_cards.csv) directly and make a Pull Request!

When you submit the pull request, please consider the following guidelines:

1. Make sure the CSV includes the correct cashback rate, and make sure that any conditions are added to the "Conditions" column
  - Conditions can include the following variable: `SPENDING` (e.g. `SPENDING > 1000` means spending exceeds BD1,000 during the month)
  - Conditions support the `AND` and `OR` boolean operators
2. Make sure to include a source link!
3. If there are any details that are not published at the source link, add them to the [Claims](https://github.com/amal-ai/bahrain-banks/blob/master/data/claims.csv) file as well