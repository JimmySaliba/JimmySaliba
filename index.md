<html>
<body>

  <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DFV000000GaYz',
				'ChatBot_Message',
				'https://power-platform-8276--jahezdev1.sandbox.my.site.com/ESWChatBotMessage1730982767983',
				{
					scrt2URL: 'https://power-platform-8276--jahezdev1.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://power-platform-8276--jahezdev1.sandbox.my.site.com/ESWChatBotMessage1730982767983/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>
  
</html>
