# NexGest — downloads

Instaladores oficiais do **NexGest**, o sistema de gestão para lojas: vendas (PDV), senhas e
atendimento, ordens de serviço, caixa, ponto, cadastro de pessoas e catálogo, com WhatsApp
integrado.

> **O jeito recomendado de instalar é pelo site:** [nexgest.app.br](https://nexgest.app.br/).
> Lá você cria a conta da loja, baixa o instalador certo e ativa a licença. Esta página guarda os
> mesmos arquivos de cada versão, para quem precisa de uma versão específica ou do link direto.

## Qual arquivo baixar

Todos os arquivos estão em **[Releases](https://github.com/nexgest/downloads/releases)**. Cada
produto tem a própria linha, com a versão no nome.

| Produto | Para quê | Sistema | Arquivo |
| --- | --- | --- | --- |
| **NexGest Servidor** | O sistema da loja: o computador principal, onde ficam o banco e o WhatsApp | Windows 10/11 (64 bits) | `NexGest-Setup-<versão>.exe` |
| **NexGest Servidor (Linux)** | O mesmo sistema, em Linux | Debian, Ubuntu e derivados (64 bits) | `nexgest-servidor_<versão>_amd64.deb` |
| **NexGest Setup (Linux)** | Instalador que pergunta o que este computador vai ser | Debian, Ubuntu e derivados (64 bits) | `nexgest-instalador_<versão>_amd64.deb` |
| **NexGest Atendimento (Linux)** | Os outros computadores do balcão, ligados ao Servidor | Debian, Ubuntu e derivados (64 bits) | `nexgest-atendimento_<versão>_amd64.deb` |
| **NexGest Atendimento (Android)** | O app do celular para atender, chamar senhas e responder conversas | Android | `NexGest-Atendimento-<versão>.apk` |
| **NexGest TV (Android)** | A TV da loja: chamada de senhas, mídia e YouTube | Android TV / TV box | `NexGest-TV-<versão>.apk` |

No Windows, o mesmo `NexGest-Setup` instala o Servidor ou o Atendimento: ele pergunta na
instalação.

## Como instalar

**Windows:** baixe o `NexGest-Setup-<versão>.exe`, abra e siga as telas. Se o Windows avisar
que o arquivo veio da internet, clique em *Mais informações* → *Executar assim mesmo*.

**Linux:** baixe o `.deb` e instale com dois cliques pela central de programas, ou pelo
terminal:

```bash
sudo apt install ./nexgest-instalador_<versão>_amd64.deb
```

**Android:** abra esta página no **Chrome** (não dentro de outro app, como o WhatsApp ou o
Instagram, onde o download costuma parar em 100%), baixe o `.apk` e toque em *Abrir*. Na primeira
vez, o Android pede para permitir a instalação de apps desta fonte.

## Atualizações

Depois de instalado, o NexGest se atualiza sozinho: o aviso aparece no próprio sistema, e um
clique baixa e instala a versão nova. Só é preciso baixar daqui de novo para reinstalar ou para
pular de uma versão muito antiga.

## Ajuda

Dúvidas, licença e suporte: [nexgest.app.br](https://nexgest.app.br/). No sistema, use
**Relatar um problema** para mandar o aviso direto para a equipe.
