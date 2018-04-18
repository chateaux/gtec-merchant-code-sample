[HOME](README.md) > SGS Slots

## SGS Slots
SGS Universal offers a variety of slots and table games. We quite like them and include most of their games in the brands that we build.

You will require the following data when adding this game to your casino:

* Your merchant account UUID from our [sandbox](https://sandbox.gamblingtec.com).
* The SGS game code: a8d19229-eebc-4e31-b78b-2a68a6f08a39
* The SGS launch URL: https://sgs.gamblingtec.com/wrapper/launch/{{game-code}}/{{FUN|REAL}}
* A list of SGS [game names and ids](sgs/game-list.php)

### How to integrate
Our favourite SGS game is The Mummy, you can play it for FUN right now by going to this URL:  https://sgs.gamblingtec.com/wrapper/launch/slmu/FUN

To play this game for real money you must send the user to our deposit/transfer page with a redirect to the game. We use the following
javascript method to achieve this:

    var baseUrl = 'https://sandbox.gamblingtec.com/';
    var gameCode = '884d6dfc-9933-45fe-af64-d8bc8b7e5f43';

    function launch(gameType, gameId) {
        var url = 'https://sgs.gamblingtec.com/wrapper/launch/' + gameId + '/' + gameType;
        if (gameType == 'REAL') {
          url = baseUrl + 'widget/launch/' + gameCode + '?type=deposit&return=' + encodeURIComponent(url);
        }
        $('#gameFrame').attr('src', url); //inject the url into the modal
        $('#gameModal').modal('show');  //show the modal
    }

Take a look at [bootstrap lobby](https://github.com/sunsevennv/gamblingtec-code-samples/tree/master/lobby-bootstrap) to see how we have integrated SGS games
into the GamblingTec.com system.

## Example site
The following is our official lottery website and we have SGS slots integrated into it: [Sunseven Lottery](https://www.sun7lottery.com/slots)
