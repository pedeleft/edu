{
  "Version": "1.0.6",
  "ReleaseNotes": "@VEM_BRABO\nconfigs novas para todas as operadoras",
  "UrlUpdate": "",
  "Sms": "",
  "EmailFeedback": "pedeleft14@gmail.com",
  "UrlContato": "",
  "UrlTermos": "",
  "CheckUser": "true",
  "UdpPort": "7100;7200;7300;7400;7500;7600;7700",
  "Servers": [
    {
      "Name": "SERVIDOR BR",
      "TYPE": "premium",
      "FLAG": "br.png",
      "ServerIP": "br9875.pedeleft14.online",
      "CheckUser": "http://144.22.249.224:5454/checkUser",
      "ServerPort": "22",
      "SSLPort": "443",
      "USER": "",
      "PASS": ""
    }
  ],
"Networks": [
    {
      "Name": "🔵TIM [01]",
      "FLAG": "tim",
      "Payload": "GET wss://texugo.alura.com.br  HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "texugo.alura.com.br",
      "TlsIP": "172.67.188.168",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🔵TIM [02]",
      "FLAG": "tim",
      "Payload": "GET wss://static.r4you.co  HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "static.r4you.co",
      "TlsIP": "104.26.5.175",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🔵TIM [03]",
      "FLAG": "tim",
      "Payload": "GET wss://static.r4you.co  HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "static.r4you.co",
      "TlsIP": "104.26.4.175",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🔵TIM [04]",
      "FLAG": "tim",
      "Payload": "GET wss://static.r4you.co  HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "static.r4you.co",
      "TlsIP": "172.67.70.43",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🔵TIM [05]",
      "FLAG": "tim",
      "Payload": "GET wss://blog.alura.com.br  HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "blog.alura.com.br",
      "TlsIP": "104.21.84.78",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🔵TIM [06]",
      "FLAG": "tim",
      "Payload": "GET wss://empresas.alura.com.br  HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "empresas.alura.com.br",
      "TlsIP": "172.64.147.215",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🔵TIM [07]",
      "FLAG": "tim",
      "Payload": "GET wss://www.alura.com.br  HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "www.alura.com.br",
      "TlsIP": "172.67.188.168",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🟣VIVO [01]",
      "FLAG": "vivo",
      "Payload": "GET wss://money-staging.infinitepay.io/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "money-staging.infinitepay.io",
      "TlsIP": "104.18.7.80",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🟣VIVO [02]",
      "FLAG": "vivo",
      "Payload": "GET wss://carrinho-pos-familia.vivo.com.br// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "carrinho-pos-familia.vivo.com.br",
      "TlsIP": "104.18.6.80",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🟣VIVO [03]",
      "FLAG": "vivo",
      "Payload": "GET wss://help.pornhub.com// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "help.pornhub.com",
      "TlsIP": "162.159.135.63",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🟣VIVO [04]",
      "FLAG": "vivo",
      "Payload": "GET wss://support.uptodown.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "support.uptodown.com",
      "TlsIP": "162.159.136.63",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🟣VIVO [05]",
      "FLAG": "vivo",
      "Payload": "GET wss://support.pokemon.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "support.pokemon.com",
      "TlsIP": "172.64.130.2",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🟣VIVO [06]",
      "FLAG": "vivo",
      "Payload": "GET wss://checkout.mediafire.com// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "checkout.mediafire.com",
      "TlsIP": "104.24.11.16",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🟣VIVO [07]",
      "FLAG": "vivo",
      "Payload": "GET wss://onepiece.com// HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: Websocket[crlf]Connection: Keep-Alive[crlf]Connection: Keep-Alive[crlf][crlf]",
      "SNI": "onepiece.com",
      "TlsIP": "172.64.131.2",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🔴CLARO [01]",
      "FLAG": "claro",
      "Payload": "GET wss://go.kaltura.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "go.kaltura.com",
      "TlsIP": "104.17.74.206",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🔴CLARO [02]",
      "FLAG": "claro",
      "Payload": "GET wss://ct.livestream.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "ct.livestream.com",
      "TlsIP": "104.17.72.206",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🔴CLARO [03]",
      "FLAG": "claro",
      "Payload": "GET wss://br.corp.kaltura.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "br.corp.kaltura.com",
      "TlsIP": "104.21.67.158",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🔴CLARO [04]",
      "FLAG": "claro",
      "Payload": "GET wss://communitystaging.kaltura.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "communitystaging.kaltura.com",
      "TlsIP": "162.159.128.79",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🔴CLARO [05]",
      "FLAG": "claro",
      "Payload": "GET wss://lp.livestream.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "stage-corp.kaltura.com",
      "TlsIP": "104.21.67.158",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🔴CLARO [06]",
      "FLAG": "claro",
      "Payload": "GET wss://vimeo.livestream.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "vimeo.livestream.com",
      "TlsIP": "104.17.71.206",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🔴CLARO [07]",
      "FLAG": "claro",
      "Payload": "GET wss://learning.kaltura.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "learning.kaltura.com",
      "TlsIP": "162.159.135.91",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🔴CLARO [08]",
      "FLAG": "claro",
      "Payload": "GET wss://icanhazip.com/ HTTP/1.1[crlf]Host: [app_host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "icanhazip.com",
      "TlsIP": "104.18.115.97",
      "ProxyIP": "",
      "ProxyPort": "443",
      "Info": "Tlsws"
   },
    {
      "Name": "🟡OI [01]",
      "FLAG": "oi",
      "Payload": "GET ws://www.hbogo.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "www.hbogo.com.br",
      "TlsIP": "104.16.55.91",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
   },
    {
      "Name": "🟡OI [02]",
      "FLAG": "oi",
      "Payload": "GET ws://www.hbogo.com.br HTTP/1.1\nHost: [app_host]\nUpgrade: ws\n\n",
      "SNI": "www.hbogo.com.br",
      "TlsIP": "104.16.53.91",
      "ProxyIP": "",
      "ProxyPort": "",
      "Info": "Tlsws"
   },
    {
      "Name": "🟡OI [03]",
      "FLAG": "oi",
      "Payload": "GET \/ HTTP\/1.3[crlf]Host: [host][crlf]Upgrade: websocket[crlf][crlf]",
      "SNI": "oii.gdmhost.ga",
      "TlsIP": "104.16.56.6",
      "ProxyIP": "104.16.56.6",
      "ProxyPort": "",
      "Info": "Tlsws"


    }
  ]
}
