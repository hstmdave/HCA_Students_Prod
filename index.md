<head>
	<body>
		<script type='text/javascript'>
			function initEmbeddedMessaging() {
				try {
				embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
	
				embeddedservice_bootstrap.init(
					'00D300000006Vym',
					'Messaging_HCA_Student',
					'https://healthstream.my.site.com/ESWMessagingHCAStudent1756133068162',
					{
						scrt2URL: 'https://healthstream.my.salesforce-scrt.com'
					}
				);
				} catch (err) {
				console.error('Error loading Embedded Messaging: ', err);
				}
			};
		</script>
		<script type='text/javascript' src='https://healthstream.my.site.com/ESWMessagingHCAStudent1756133068162/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

	</body>
 
</head>
