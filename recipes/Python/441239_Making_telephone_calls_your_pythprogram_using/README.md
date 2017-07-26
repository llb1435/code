## Making telephone calls from your python program using Voicent Gateway

Originally published: 2005-10-13 16:28:19
Last updated: 2005-10-13 16:28:19
Author: Andrew Kern

The Voicent Python Simple Interface class contains the following functions.\n\n    callText\n    callAudio\n    callStatus\n    callRemove\n    callTillConfirm\n\nThese functions are used to invoke telephone calls from your Python program. For example, callText is used to call a specified number and automatically play your text message using text-to-speech engine.\n\nIn order for this class to work, you'll need to have Voicent Gateway installed somewhere in your network. This class simply sends HTTP request for telephone calls to the gateway. Voicent has a free edition for the gateway. You can download it from http://www.voicent.com\n\nMore information can be found at:\nhttp://www.voicent.com/devnet/docs/pyapi.htm