💻 Hacker Chat Host - AnyDesk ID via P2P

Este projeto é uma interface web estilizada no estilo hacker (verde-neon em fundo preto) que utiliza PeerJS para criar uma comunicação direta peer-to-peer (P2P) entre dois navegadores. O objetivo principal é permitir que, ao executar um script .bat gerado, o cliente envie automaticamente o código do AnyDesk para o host.

🚀 Funcionalidades

Interface terminal hacker (monoespaçada, verde-neon).

Gera e permite o download de um arquivo .bat a partir de um template .cdfb.

Substitui automaticamente o placeholder seuidaqui pelo ID do host gerado pelo PeerJS.

Envia o conteúdo via conexão P2P diretamente para o navegador do host.

Caixa de mensagens para comunicação bidirecional em tempo real.

🧪 Tecnologias Usadas

HTML5, CSS3 e JavaScript puro

PeerJS (para conexão P2P via WebRTC)

📁 Como Usar

Abra o arquivo host.html no navegador.

Clique no botão Importar Arquivo e selecione o arquivo base.cdfb.

O ID do host será automaticamente inserido no local do placeholder seuidaqui.

Clique no botão Baixar .bat para gerar e baixar o arquivo .bat com o ID do host.

Envie esse arquivo .bat para o usuário que deseja se conectar.

Quando o usuário executar o .bat, o código será enviado automaticamente via P2P para você (host).

⚠️ Atenção: toda vez que a página for atualizada, o ID do host será perdido e será necessário repetir o processo (abrir, importar, gerar e reenviar o .bat).

⚠️ Aviso Legal

Este projeto é fornecido apenas para fins educacionais. O uso indevido pode ser considerado ilegal. O autor não se responsabiliza por quaisquer danos causados. Use com responsabilidade e sempre com o consentimento das partes envolvidas.

📷 Capturas de Tela
![image](https://github.com/user-attachments/assets/9782b794-1153-41d1-8d21-e0a4a5bd3921)


🤝 Contribuições

Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias e correções.
