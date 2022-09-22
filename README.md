{
  "Version": "1.0.0",
  "ReleaseNotes": "Nova Atualização Disponível",
  "UrlUpdate": "https://github.com/974084866/VIVO/blob/main/README.md",
  "Sms": "BOTAR LINK DO SMS AQUI",
  "EmailFeedback": "https://t.me/davi_drm",
  "UrlContato": "http://wa.me/+5511933777718",
  "UrlTermos": "https://davxdroid.xyz/Conecta4g_site/termos.html",
  "CheckUser": "true",
  "Udp": [
    {
      "Porta": "7300"
    }
  ],
  "Servers": [
    {
      "Name": "Servidor BR",
      "TYPE": "premium",
      "FLAG": "br.png",
      "ServerIP": "br.davxdroid.xyz",
      "CheckUser": "http://38.9.119.99:5454/checkUser",
      "ServerPort": "22",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    }
  ],
  "Networks": [
    {
      "Name": "TIM  ON",
      "FLAG": "tim",
      "Payload": "GET wss://image.mail.c6bank.com.br/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "image.mail.c6bank.com.br",
      "TlsIP": "104.16.236.16",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM [SSL 1]",
      "FLAG": "tim",
      "Payload": "GET wss://image.mail.c6bank.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "image.mail.c6bank.com.br",
      "TlsIP": "image.mail.c6bank.com.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM [SSL 2]",
      "FLAG": "tim",
      "Payload": "GET ws://ajuda.c6bank.com.br HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf]Sec-Websocket-Extensions: superspeed[crlf][crlf]",
     "SNI": "ajuda.c6bank.com.br",
     "TlsIP": "104.16.236.16",
     "ProxyIP": "",
     "ProxyPort": "443",
     "Info": "Tlsws"
    },
    {
      "Name": "TIM [SSL 3]",
      "FLAG": "tim",
      "Payload": "GET wss://image.mail.c6bank.com.br/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "image.mail.c6bank.com.br",
      "TlsIP": "104.16.236.16",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM [SSL 4]",
      "Name": "TIM",
      "FLAG": "tim",
      "Payload": "GET wss://auth.of.c6bank.com.br/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: mentalista[crlf][crlf]",
      "SNI": "auth.of.c6bank.com.br",
      "TlsIP": "172.64.144.237",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "VIVO   [ 1 ]",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Upgrade[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.18.7.80",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "VIVO  [ 2 ]",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.18.6.80",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "VIVO [SSL 3]",
      "FLAG": "vivo",
      "Payload": "GET wss://legado.vivo.com.br// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "legado.vivo.com.br",
      "TlsIP": "legado.vivo.com.br",
      "ProxyIP": "104.18.7.80",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "VIVO   [ 4 ]",
      "FLAG": "vivo",
      "Payload": "GET wss://snow.vivo.com.br/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Upgrade[crlf][crlf]",
      "SNI": "snow.vivo.com.br",
      "TlsIP": "snow.vivo.com.br",
      "ProxyIP": "104.18.6.80",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "VIVO  [ ✈️ ]",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "162.247.241.14",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "VIVO [SSL  ✈️ 1 ]",
      "FLAG": "vivo",
      "Payload": "GET wss://unpkg.com// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "unpkg.com",
      "TlsIP": "162.247.241.14",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "VIVO [SSL  ✈️ 2 ]",
      "FLAG": "vivo",
      "Payload": "GET ws://unpkg.com HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "unpkg.com",
      "TlsIP": "unpkg.com",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "CLARO [SSL 1]",
      "FLAG": "claro",
      "Payload": "GET wss://go.launchdarkly.com HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "go.launchdarkly.com",
      "TlsIP": "go.launchdarkly.com",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "CLARO [SSL 2]",
      "FLAG": "claro",
      "Payload": "GET wss://go.launchdarkly.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "go.launchdarkly.com",
      "TlsIP": "go.launchdarkly.com",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "️CLARO [SSL 3]",
      "FLAG": "claro",
      "Payload": "GET GET wss://go.launchdarkly.com HTTP/1.1[crlf]Host: [app_host][crlf]Connection: upgrade[crlf]Upgrade: websocket [crlf][crlf]",
      "SNI": "go.launchdarkly.com",
      "TlsIP": "go.launchdarkly.com",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "CLARO [SSL4]",
      "FLAG": "claro",
      "Payload": "GET wss://"player-api.new.livestream.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": ""player-api.new.livestream.com",
      "TlsIP": ""player-api.new.livestream.com",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "CLARO [SSL5]",
      "FLAG": "claro",
      "Payload": "GET wss://ct.livestream.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "ct.livestream.com",
      "TlsIP": "ct.livestream.com",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
   {
      "Name": "Oi [SSL 1]",
      "FLAG": "oí",
      "Payload": "GET wss://www.hbogo.com.br HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "www.hbogo.com.br",
      "TlsIP": "104.16.53.91",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
   {
      "Name": "OI [SSL 1]",
      "FLAG": "oi",
      "Payload": "GET ws://www.hbogo.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "www.hbogo.com.br",
      "TlsIP": "www.hbogo.com.br",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "OI [SSL 2]",
      "FLAG": "oi",
      "Payload": "GET ws://www.hbogo.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "www.hbogo.com.br",
      "TlsIP": "104.16.53.91",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    }
  ]
}
