<style type='text/css'>
	.embeddedMessagingConversationButtonWrapper .embeddedMessagingConversationButton {
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
	}
	.embeddedMessagingConversationButtonWrapper .embeddedMessagingConversationButton:focus {
		outline: 1px solid #0081A1;
	}
	.lwc-c5th8h1hm8-host {
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
	}

        .slds-icon-utility-minimize-window{
    		zoom: 120%;
	 }       
    	 .slds-icon-utility-close{
          	zoom: 120%;
     	  }
    
    	 .slds-form-element__label{
        	font-size:1.5ch;
       	}
</style>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00Ddp000000semr',
				'Live_Chat_Embedded_Deployment',
				'https://haporg--apmdev.sandbox.my.site.com/ESWHAPMedicareBotDeplo1736420918060',
				{
					scrt2URL: 'https://haporg--apmdev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://haporg--apmdev.sandbox.my.site.com/ESWHAPMedicareBotDeplo1736420918060/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
