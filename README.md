{
  "Version": "2.0.0",
  "ReleaseNotes": "Nova Atualização Disponível",
  "UrlUpdate": "https://github.com/974084866/VIVO/blob/main/README.md",
  "Sms": "BOTAR LINK DO SMS AQUI",
  "EmailFeedback": "vicorojo@gmail.com",
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
      "Name": "VIVO VÍDEO [SSL 1]",
      "FLAG": "vivo",
      "Payload": "GET wss://portaljud.vivo.com.br// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "portaljud.vivo.com.br",
      "TlsIP": "104.18.7.80",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM [SSL 1]",
      "FLAG": "tim",
      "Payload": "GET wss://static.r4you.co  HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "static.r4you.co",
      "TlsIP": "static.r4you.co",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM [SSL 2]",
      "FLAG": "tim",
      "Payload": "GET wss://static.r4you.co HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "static.r4you.co",
      "TlsIP": "104.26.5.175",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM [SSL 3]",
      "FLAG": "tim",
      "Payload": "GET wss://static.r4you.co/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "static.r4you.co",
      "TlsIP": "172.67.70.43",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM 5",
      "FLAG": "tim",
      "Payload": "GET wss://blog.alura.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "blog.alura.com.br",
      "TlsIP": "104.18.40.41",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM [SSL 5]",
      "FLAG": "tim",
      "Payload": "GET wss://empresas.alura.com.br  HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "empresas.alura.com.br",
      "TlsIP": "104.18.40.41",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "VIVO [DIRECT 1]",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "104.18.7.80",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "VIVO [DIRECT 2]",
      "FLAG": "vivo",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "",
      "TlsIP": "",
      "ProxyIP": "162.159.136.63",
      "ProxyPort": "80",
      "Info": "Proxy"
    },
    {
      "Name": "VIVO [SSL 1]",
      "FLAG": "vivo",
      "Payload": "GET wss://money-staging.infinitepay.io/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "money-staging.infinitepay.io",
      "TlsIP": "104.18.7.80",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "VIVO [SSL 2]",
      "FLAG": "vivo",
      "Payload": "GET wss://carrinho-pos-familia.vivo.com.br// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "carrinho-pos-familia.vivo.com.br",
      "TlsIP": "162.159.136.63",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "VIVO [SSL 3]",
      "FLAG": "vivo",
      "Payload": "GET wss://portaljud.vivo.com.br// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "portaljud.vivo.com.br",
      "TlsIP": "162.159.135.63",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "CLARO [SSL 1]",
      "FLAG": "claro",
      "Payload": "GET wss://videos.kaltura.com HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "videos.kaltura.com",
      "TlsIP": "162.159.135.91",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "CLARO [SSL 2]",
      "FLAG": "claro",
      "Payload": "GET wss://vimeo.livestream.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "vimeo.livestream.com",
      "TlsIP": "vimeo.livestream.com",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "️CLARO [SSL 3]",
      "FLAG": "claro",
      "Payload": "GET GET wss://icanhazip.com HTTP/1.1[crlf]Host: [app_host][crlf]Connection: upgrade[crlf]Upgrade: websocket [crlf][crlf]",
      "SNI": "icanhazip.com",
      "TlsIP": "icanhazip.comt",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "CLARO [SSL4]",
      "FLAG": "claro",
      "Payload": "GET wss://br.corp.kaltura.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "br.corp.kaltura.com",
      "TlsIP": "br.corp.kaltura.com",
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
