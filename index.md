<html>
  <body>
    <script type="text/javascript">
      function initEmbeddedMessaging() {
        try {
          embeddedservice_bootstrap.settings.language = "en_US"; // For example, enter 'en' or 'en-US'

          embeddedservice_bootstrap.init(
            "00DdM000004MuMD",
            "sample_chat",
            "https://rcg-dev-ed.develop.my.site.com/ESWsamplechat1718119128102",
            {
              scrt2URL: "https://rcg-dev-ed.develop.my.salesforce-scrt.com",
            }
          );

          console.log('Success');
        } catch (err) {
          console.error("Error loading Embedded Messaging: ", err);
        }
      }
    </script>
    <script
      type="text/javascript"
      src="https://rcg-dev-ed.develop.my.site.com/ESWsamplechat1718119128102/assets/js/bootstrap.min.js"
      onload="initEmbeddedMessaging()"
    ></script>
  </body>
</html>
