# TestFlight Module

### testflight.customInfo('', '')
These are environment based details, so it won't track changes in the data.
For example you might use this for a username of the tester within your app.

### testflight.checkpoint('')

#### Arguments

Takes one argument, a string which is the name for your checkpoint

### testflight.feedback()

Show the feedback dialog

## Usage

      var testflight = require('ti.testflight');
   
      testflight.token('YourTeamTokenHere');
   
      testflight.checkpoint('SomeCheckpoint');
   
      testflight.feedback();
   

## Authors

Rick Blalock
Twitter: rblalock

Matt Apperson
Twitter: mattapperson

## License

Apache Public License 2.0