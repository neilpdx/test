sed -i \
      -e 's/;newrelic.browser_monitoring.auto_instrument = true/newrelic.browser_monitoring.auto_instrument = false/' \
      /etc/php/7.4/apache2/conf.d/newrelic.ini
