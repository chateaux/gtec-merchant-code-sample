[HOME](README.md) > SUNSEVEN LOTTERY

## Sunseven Lottery Games
Sunseven Lottery offers a play on world lottery games. This is offered as either a multi-tenant solution or a bespoke solution.

You will require the following data when adding this game to your casino:

* Web app location: https://lottery.gamblingtec.com
* Our Lottery API which delivers game and result information and is provided on request.
* Your merchant account UUID from our [sandbox](https://sandbox.gamblingtec.com).

### How to integrate
In general, the api will deliver relevant lottery information to your casino brand. The brand, in turn, will provide a play link as part of
ts display which, when clicked, will launch the relevant lottery games in the web app.

It is our preference to load the web app inside a modal/iframe combination which keeps the user on your branded casino website.

Once the game has been launched, the player selects numbers and makes the required payment via the GamblingTec.com payment pages.

On completion, they simply close the modal page in order to return to your website.

We would suggest taking a look at the [bootstrap lobby](https://github.com/sunsevennv/gamblingtec-code-samples/tree/master/lobby-bootstrap)
for technical information in terms of integrating your casino.

### Advanced setup
It is possible to use the api to build a unique lottery ticket form and to re-direct players to the payment pages as the final step.

An advanced option would take some time to create and we would suggest using the re-direct method as an interim solution.

## Example site
The following is our official lottery website: [Sunseven Lottery](https://www.sun7lottery.com)
