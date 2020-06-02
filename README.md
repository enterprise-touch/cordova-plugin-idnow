# cordova-plugin-idnow

IDNOW plugin for Cordova.

Android supported.
iOS Support will be coming soon.

Install with Cordova CLI:

$ cordova plugin add https://github.com/enterprise-touch/cordova-plugin-idnow.git

Supported Platforms:

* Android

## API



    /**
	 * Loads Native SDK of ID-NOW.
	 */
	        
            window.plugins.idNow.sendData(dataToSend,onSuccess,onError);
                   

            function onSuccess(msg) {
               //Hangle Success
            }

            function onError(msg) {
                    //Hangle Error
                }

## Example Usage

        window.plugins.idNow.sendData(dataToSend,onSuccess,onError);

            function onSuccess(msg) {
                alert(msg);
            }

            function onError(msg) {
                    alert(msg);
                }
