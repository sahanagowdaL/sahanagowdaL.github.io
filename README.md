<style type='text/css'>
	.embeddedMessagingConversationButtonWrapper .embeddedMessagingConversationButton {
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
	}
	.embeddedMessagingConversationButtonWrapper .embeddedMessagingConversationButton:focus {
		outline: 1px solid #0081A1;
	}
	.minimizedButton-20.slds-button.minimizedButton{
		background-color: var(--headerColor, var(--lwc-brandContrast, #0081A1))
		background-color: #0081A1;
	}
	.minimizedButtonWrapper[lwc-2tu55qmbbaf] .minimizedButton[lwc-2tu55qmbbaf] {
		background-color: var(--headerColor, var(--lwc-brandContrast, #0081A1))
		background-color: #0081A1;
	}
	.minimizedButtonWrapper .minimizedButton-20{
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
	}
	.minimizedButtonWrapper .minimizedButton .minimizedButton-20{
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
	}
	.minimizedButtonWrapper .slds-button minimizedButton{
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
	}
	.minimizedButtonWrapper .slds-button minimizedButton .minimizedButton-20{
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
	}
	.embeddedmessaging-container.embeddedmessaging-chat-header.containerArea{
		background-color: var(--headerColor, var(--lwc-brandContrast, #0081A1));
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
		headerColor:#0081A1;
	}
	.container-2ccc.containerArea{
		background-color: var(--headerColor, var(--lwc-brandContrast, #0081A1));
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
		headerColor:#0081A1;
	}
	.header.chatHeader{
		background-color: var(--headerColor, var(--lwc-brandContrast, #0081A1));
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
		headerColor:#0081A1;
	}
	[lwc-c5th8h1hm8-host]{
		background-color: var(--headerColor, var(--lwc-brandContrast, #0081A1));
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
		headerColor:#0081A1;
	}
	.chatHeader[lwc-c5th8h1hm8]{
		background-color: var(--headerColor, var(--lwc-brandContrast, #0081A1));
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
		headerColor:#0081A1;
	}
	.embeddedmessaging-chat-header .containerArea{
		background-color: var(--headerColor, var(--lwc-brandContrast, #0081A1));
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
		headerColor:#0081A1;
	}
	.containerArea{
		background-color: var(--headerColor, var(--lwc-brandContrast, #0081A1));
		background-color: #0081A1;
		font-family: "Chivo", sans-serif;
		headerColor:#0081A1;
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
	.custom-header {
		color: black;
		font-size: 2em;
		text-align: center;
		margin: 20px 0;
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

<div class="custom-header">
	<h1>Testing</h1>
</div>
