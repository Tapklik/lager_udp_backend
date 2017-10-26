
Add in app.config

{lager, [
		{handlers, [
			{lager_udp_backend, [
				{name,     "lager_udp_backend"},
				{level,    debug},
				{host,    "localhost"},
				{port,    20001}
       ]}
 }
