<html>
<head>
        <style>
            html, body {
                margin: 0;
                padding: 0;
                height: 100%;
                width: 100%;
                overflow: hidden;
                font-family: Arial, sans-serif;
            }

            #customWaitingMessage {
                display: none;
                position: absolute;
                top: 0;
                left: 0;
                right: 0;
                bottom: 0;
                background: #f5f5f5;
                text-align: center;
                vertical-align: middle;
                justify-content: center;
                align-items: center;
                font-size: 18px;
                color: #333;
                z-index: 1000;
            }
        </style>
    </head>
    <h2>Contact Support</h2>
    <p>Click the chat icon in the bottom-right corner to start a conversation.</p>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00Ddu000007FkJR',
				'CD_Online_Internal',
				'https://partners-cdfxservices--sit.sandbox.my.site.com/ESWCDOnlineInternal1749127303273',
				{
					scrt2URL: 'https://partners-cdfxservices--sit.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://partners-cdfxservices--sit.sandbox.my.site.com/ESWCDOnlineInternal1749127303273/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</html>
