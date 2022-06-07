
{
  "Version": "1.0.0",
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
      "Payload": "GET wss://cdnjs.cloudflare.com  HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "cdnjs.cloudflare.com",
      "TlsIP": "104.16.19.94",
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
      "Payload": "GET wss://beringtime.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "beringtime.com",
      "TlsIP": "104.16.18.94",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM [SSL 4]",
      "FLAG": "tim",
      "Payload": "GET ws://cutim.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "cutim.com.br",
      "TlsIP": "104.16.19.94",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
    },
    {
      "Name": "TIM [SSL 5]",
      "FLAG": "tim",
      "Payload": "GET / HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "[app_host]",
      "TlsIP": "104.16.19.94",
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
      "ProxyIP": "vigia.vivo.com.br",
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
      "TlsIP": "104.18.6.80",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "VIVO [SSL 3]",
      "FLAG": "vivo",
      "Payload": "GET wss://portaljud.vivo.com.br// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "portaljud.vivo.com.br",
      "TlsIP": "104.18.7.80",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "️CLARO [SSL 1]",
      "FLAG": "claro",
      "Payload": "GET wss://api.new.livestream.com HTTP/1.1[crlf]Host: [app_host][crlf]Connection: upgrade[crlf]Upgrade: websocket [crlf][crlf]",
      "SNI": "api.new.livestream.com",
      "TlsIP": "api.new.livestream.com",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "️CLARO [SSL 2]",
      "FLAG": "claro",
      "Payload": "GET GET wss://icanhazip.com HTTP/1.1[crlf]Host: [app_host][crlf]Connection: upgrade[crlf]Upgrade: websocket [crlf][crlf]",
      "SNI": "icanhazip.com",
      "TlsIP": "icanhazip.comt",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "️CLARO [SSL 3]",
      "FLAG": "claro",
      "Payload": "GET wss://Atendimento.descomplica.com.br HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: covid[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "Atendimento.descomplica.com.br",
      "TlsIP": "199.60.103.228",
      "ProxyIP": "No.descomplica.com.br",
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
      "ProxyPort": "443",
      "Info": "Tlsws"
    },
    {
      "Name": "OI [SSL 2]",
      "FLAG": "oi",
      "Payload": "GET wss://www.hbogo.com.br HTTP/1.1[crlf]Host: [app_host][crlf]Connection: upgrade[crlf]Upgrade: websocket [crlf][crlf]",
      "SNI": "www.hbogo.com.br",
      "TlsIP": "104.16.53.91",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
    }
  ]
}
