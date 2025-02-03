<style type='text/css'>
	.embeddedMessagingConversationButtonWrapper .embeddedMessagingConversationButton {
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
	}
	.embeddedMessagingConversationButtonWrapper .embeddedMessagingConversationButton:focus {
		outline: 1px solid #0081A1;
	}

	.chatHeader[lwc-c5th8h1hm8]{
		background-color: #0081A1;
		color: #0081A1;
		font-family: "Chivo", sans-serif;
	}
	.chatHeader{
		background-color: #0081A1;
		color: #0081A1;
		font-family: "Chivo", sans-serif;
	}

	.embeddedmessaging-chat-header, 
	.embeddedmessaging-chat-header.containerArea, 
	.lwc-c5th8h1hm8-host {
		background-color: #0081A1 !important;
		color: #FFFFFF !important;
	}

	.embeddedmessaging-chat-header{
		background-color: #0081A1;
		background-color: #0081A1 !important;
		color: #0081A1;
		font-family: "Chivo", sans-serif;
	}
	.embeddedmessaging-chat-header.containerArea{
		background-color: #0081A1;
		color: #0081A1;
		font-family: "Chivo", sans-serif;
	}
	.containerArea{
		background-color: #0081A1;
		color: #0081A1;
		font-family: "Chivo", sans-serif;
	}
	.header.chatHeader{
		background-color: #0081A1;
		Background : #0081A1;
		font-family: "Chivo", sans-serif;
	}
	.lwc-c5th8h1hm8-host {
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
	}
	[lwc-c5th8h1hm8-host]{
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
				'00Ddl000001XOKj',
				'Live_Chat_Embedded_Deployment',
				'https://haporg--devmerge.sandbox.my.site.com/ESWLiveChatEmbeddedDep1738126593973',
				{
					scrt2URL: 'https://haporg--devmerge.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://haporg--devmerge.sandbox.my.site.com/ESWLiveChatEmbeddedDep1738126593973/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
