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
    <body>
    <h2>Contact Support</h2>
    <p>Click the chat icon in the bottom-right corner to start a conversation.</p>
	<input type="text" id="myHtmlInput1" />
    <input type="text" id="myHtmlInput2" />
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00Ddu000007FkJR',
				'CD_PFX_Embedded_Service_Deployment_MIAW',
				'https://partners-cdfxservices--sit.sandbox.my.site.com/ESWCDPFXEmbeddedServic1759300579641',
				{
					scrt2URL: 'https://partners-cdfxservices--sit.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
		window.addEventListener("onEmbeddedMessagingReady",() => {
            embeddedservice_bootstrap.prechatAPI.setHiddenPrechatFields({"CDH_Company":"Currencies Direct","CustomerType":"PFX","ChatSource":"Support","FirstName":"TorFX CFX Support","ContactId":"003du00000Aliz7AAB","CaseId":"","Origin":"NGOP"}) 
    }); 
	};
</script>
<script type='text/javascript' src='https://partners-cdfxservices--sit.sandbox.my.site.com/ESWCDPFXEmbeddedServic1759300579641/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

<!--<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DgK00000528cv',
				'Custom_Agentforce_deployment',
				'https://orgfarm-9c41538cc3-dev-ed.develop.my.site.com/ESWCustomAgentforcedepl1750079811755',
				{
					scrt2URL: 'https://orgfarm-9c41538cc3-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://orgfarm-9c41538cc3-dev-ed.develop.my.site.com/ESWCustomAgentforcedepl1750079811755/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>-->
</body>
</html>
