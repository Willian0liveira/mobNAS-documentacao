# mobNAS

**Transforme seu Android em um NAS pessoal acessível pela internet.**

mobNAS é um aplicativo que transforma qualquer celular ou tablet Android em um servidor de arquivos (NAS). Com ele, você pode acessar, compartilhar e fazer streaming dos seus arquivos de qualquer lugar sem precisar de computador, IP fixo ou configurações complicadas de rede.

---

## Índice

- [O que é o mob NAS?](#o-que-é-o-mob-nas)
- [Principais Funcionalidades](#principais-funcionalidades)
- [Primeiros Passos](#primeiros-passos)
- [Usando o Aplicativo](#usando-o-aplicativo)
- [Acessando Seus Arquivos](#acessando-seus-arquivos)
- [Compartilhando Arquivos](#compartilhando-arquivos)
- [WebDAV. Conecte Como um Disco de Rede](#webdav--conecte-como-um-disco-de-rede)
- [Streaming de Mídia](#streaming-de-mídia)
- [Acesso pela Internet com Cloudflare](#acesso-pela-internet-com-cloudflare)
- [Modo NAS (24/7)](#modo-nas-247)
- [Gerenciando Usuários](#gerenciando-usuários)
- [Monitoramento](#monitoramento)
- [Backup](#backup)
- [Perguntas Frequentes](#perguntas-frequentes)
- [Suporte e Comunidade](#suporte-e-comunidade)

---

## O que é o mob NAS?

mobNAS (Mobile NAS) é a solução para transformar aquele celular antigo ou tablet parado em um servidor de arquivos útil.

### Para que serve?

- **Centralize seus arquivos** — tenha fotos, vídeos, documentos e músicas em um só lugar
- **Acesse de qualquer lugar** — veja seus arquivos pelo celular, tablet ou computador, em casa ou fora
- **Compartilhe com facilidade** — envie links temporários para amigos e familiares
- **Faça streaming** — assista vídeos e ouça música diretamente do seu NAS
- **Economize** — use um dispositivo que você já tem em vez de comprar um NAS caro

### Vantagens

- ✅ Não precisa de computador ligado
- ✅ Não precisa de IP fixo
- ✅ Não precisa abrir portas no roteador
- ✅ Funciona 24 horas por dia
- ✅ Interface em português (e mais 7 idiomas)

---

## Principais Funcionalidades

### Servidor de Arquivos
- Navegue por pastas e arquivos
- Crie, renomeie, mova, copie e exclua arquivos
- Envie arquivos do seu celular ou computador para o NAS
- Baixe arquivos do NAS para qualquer dispositivo
- Veja fotos e vídeos em miniaturas

### Streaming de Mídia
- Assista vídeos (MP4, MKV, MOV, WEBM)
- Ouça músicas (MP3, FLAC, AAC)
- Funciona como seu próprio Netflix pessoal

### WebDAV
- Conecte-se como um disco de rede no Windows, Mac ou Linux
- Arraste arquivos diretamente do seu computador

### Compartilhamento
- Crie links para compartilhar arquivos
- Links temporários que expiram
- Links com senha (opcional)

### Acesso pela Internet
- Acesse de qualquer lugar do mundo
- Seguro e criptografado
- Sem configuração de roteador

---

## Primeiros Passos

### Instalação

1. Instale o aplicativo no seu dispositivo Android
2. Abra o mob NAS
3. Na primeira vez, você verá uma tela de boas-vindas explicando as principais funções

### Tela de Boas-Vindas

Na primeira execução, o aplicativo mostra três funcionalidades principais:
- **Servidor de Arquivos** — transforma seu dispositivo em um NAS
- **Cloudflare Tunnel** — acesso seguro pela internet
- **Modo NAS** — funciona 24 horas por dia

Toque em **"Começar"** para prosseguir.

### Tela de Login

O primeiro usuário cadastrado será o **Administrador**.

1. Acesse com login admin e senha admin, posteriormente crie um nome de usuário e senha
2. Marque "Lembrar credenciais" se quiser entrar automaticamente nas próximas vezes
3. Toque em **"Entrar"**

### Tela Principal

Após o login, você verá a tela principal com 5 abas na parte inferior:

| Aba | Descrição |
|---|---|
| **Painel** | Status do servidor, métricas e ações |
| **Arquivos** | Navegador de arquivos |
| **Usuários** | Gerenciar contas (admin) |
| **Logs** | Histórico de atividades |
| **Ajustes** | Configurações do servidor |

---

## Usando o Aplicativo

### Painel

O painel mostra um resumo do estado do seu NAS:

- **Status do Servidor** — verde se estiver rodando
- **Status do Túnel** — se o Cloudflare está conectado
- **URL Pública** — endereço para acessar de fora de casa
- **Métricas** — CPU, temperatura, memória, armazenamento, bateria
- **Health Score** — um número de 0 a 100 indicando a saúde do dispositivo

Botões importantes:
- **Iniciar Servidor** — liga o servidor
- **Parar Servidor** — desliga o servidor
- **Reiniciar** — reinicia o servidor

### Arquivos

O gerenciador de arquivos permite:

- **Navegar** — toque nas pastas para abrir
- **Voltar** — use o botão no topo para voltar
- **Alternar visualização** — escolha entre lista ou grade
- **Buscar** — procure arquivos pelo nome
- **Filtrar** — filtre por tipo (vídeos, imagens, áudios, documentos)

**Ações em arquivos/pastas:**

Toque em um arquivo ou pasta para ver as opções:

| Ação | Descrição |
|---|---|
| ⬇️ Download | Baixar para seu dispositivo |
| ✏️ Renomear | Mudar o nome |
| 📋 Copiar | Copiar para outra pasta |
| ✂️ Mover | Mover para outra pasta |
| 🔗 Compartilhar | Criar link para enviar |
| 🗑️ Excluir | Remover (definitivo) |

**Seleção múltipla:**

Toque e segure em um arquivo para ativar a seleção múltipla. Depois você pode:
- Excluir vários de uma vez
- Mover todos para outra pasta
- Copiar todos

**Upload (enviar arquivos):**

Toque no botão ➕ para enviar arquivos do seu celular para o NAS. Você pode:
- Escolher arquivos da galeria
- Escolher arquivos do gerenciador de arquivos
- Acompanhar o progresso do envio

### Usuários (Administrador)

Se você é administrador, pode gerenciar outros usuários:

- **Listar** — veja todos os usuários cadastrados
- **Criar** — adicione novos usuários
- **Editar** — mude permissões e cotas
- **Excluir** — remova usuários

**Permissões que você pode definir para cada usuário:**

| Permissão | O que permite |
|---|---|
| 👁️ Ler | Visualizar arquivos e pastas |
| ✏️ Escrever | Editar e criar arquivos |
| ⬆️ Enviar | Fazer upload |
| ⬇️ Baixar | Fazer download |
| 🗑️ Excluir | Remover arquivos |
| 🔗 Compartilhar | Criar links |
| ▶️ Streaming | Assistir vídeos e ouvir música |
| ⚙️ Configurar | Alterar configurações |

### Logs

O histórico mostra todas as atividades do servidor:
- Logins e logouts
- Uploads e downloads
- Exclusões
- Erros

Você pode filtrar por tipo de evento e nível (info, aviso, erro).

### Ajustes

| Opção | Descrição |
|---|---|
| **Porta do Servidor** | Número da porta (padrão: 8080) |
| **Auto Start** | Ligar servidor automaticamente ao abrir o app |
| **Tema** | Claro, escuro ou automático |
| **Cloudflare** | Configurar túnel para acesso pela internet |
| **Modo NAS** | Ativar operação 24/7 |
| **Backup** | Fazer backup das configurações |
| **Sobre** | Versão, termos de uso e informações |

---

## Acessando Seus Arquivos

### Pela Rede Local (mesma casa/escritório)

1. Certifique-se de que o servidor está rodando (verde no Painel)
2. No seu computador, ou qualquer dispositivo com navegador, acesse o link de rede exibido no painel
3. Digite o endereço mostrado no Painel (ex: `http://192.168.1.10:8080`)
4. Faça login com seu usuário e senha

### Pela Internet (de qualquer lugar)

Para acessar seu NAS de fora de casa, você precisa de um túnel Cloudflare. Há duas formas de fazer isso:

#### Opção 1 — Túnel Público (try.cloudflare.com) — Mais Simples

Ideal para testes e uso ocasional. Não precisa de cadastro.

**Passo a passo:**

1. Instale o **Termux** no seu Android (baixe pelo site oficial, GooglePlay ou F-Droid)
2. No Termux, atualize os pacotes digitando e confirmando com Enter:
   ```
   pkg update
   pkg upgrade
   ```
3. Instale o cloudflared:
   ```
   pkg install cloudflared
   ```
4. Inicie o túnel (substitua 8080 pela porta do seu servidor, se tiver mudado):
   ```
   cloudflared tunnel --url localhost:8080
   ```
5. Após alguns segundos, o Termux mostrará uma URL parecida com:
   ```
   https://abc123.trycloudflare.com  ( atente-se que o link precisa conter esse " trycloudflare.com " )
   ```
6. **Pronto!** Acesse essa URL de qualquer lugar do mundo no navegador
7. Faça login com seu usuário e senha do mobNAS

> ⚠️ Essa URL muda toda vez que você reiniciar o túnel. Para uso contínuo, use a Opção 2.

#### Opção 2 — Cloudflare Zero Trust (Domínio Próprio) — Recomendado

Ideal para uso contínuo com um endereço fixo e seu próprio domínio.
Essa opção exige um cadastro de cartão para verificação de usuário, mas não se preocupe, não será cobrado nada mensalmente ou anualmente se você não ultrapassar o limite de 50 licenças.

**Passo a passo:**

1. **Crie uma conta gratuita** em [Cloudflare Zero Trust](https://dash.cloudflare.com)
2. No menu, vá em **Zero Trust > Redes** e clique em **Conectores**
3. Clique em 'Criar túnel ' e escolha um nome para o túnel (ex: `meu-nas`) e clique em **Save tunnel**
4. Na tela seguinte, Copie o link do tunnel que aparece na linha 'cloudflared.exe service install ...', remova o 'cloudflared.exe service install' deixando apenas o token. Clique em Próximo.
5. **No seu Android**, instale o Termux e execute:
   ```
   pkg update
   pkag upgrade
   pkg install cloudflared
   ```
6. Inicie o túnel com o token que você copiou:
   ```
   cloudflared tunnel run --token SEU_TOKEN_AQUI
   ```
7. De volta ao site da Cloudflare, vá em **Public Hostname Pages** e clique em **Add a public hostname**
   - **Domain**: escolha seu domínio (ex: `meudominio.com`)
   - **Subdomain**: ex: `nas`
   - **Path**: deixe vazio
   - **Type**: `HTTP`
   - **URL**: `localhost:8080`
8. Clique em **Save hostname**

**Pronto!** Agora seu NAS está acessível em:
```
https://nas.meudominio.com
```

Acesse de qualquer navegador, de qualquer lugar do mundo.

> **Vantagens do domínio próprio:** URL fixa, não muda nunca, confiável.

#### Dicas Importantes

- A URL pública aparece também no **Painel** do app (na seção de status do túnel)
- Salve a URL nos favoritos do seu navegador
- Compartilhe a URL com usuários que você cadastrou
- O túnel só funciona enquanto o Termux estiver rodando, mantenha-o aberto, somente fechado da pilha de aplicativos abertos, faça o mesmo com o app do mobNAS.

---

## Compartilhando Arquivos

Você pode compartilhar qualquer arquivo com outras pessoas:

1. No gerenciador de arquivos, toque no arquivo desejado
2. Escolha **Compartilhar**
3. Defina as opções:
   - **Link temporário** — expira em 1h, 24h ou 7 dias
   - **Link permanente** — não expira
   - **Proteger com senha** — opcional
4. Toque em **"Criar Link"**
5. Copie o link e envie para quem quiser

A pessoa não precisa ter o aplicativo só precisa do link.

---

## WebDAV — Conecte Como um Disco de Rede

O WebDAV permite montar o NAS como uma pasta do seu computador, igual a um HD externo.

### No Windows

1. Abra o **Explorador de Arquivos**
2. Clique com botão direito em **Este Computador**
3. Escolha **Mapear unidade de rede**
4. Digite: `https://<seu-endereco>/webdav/`
5. Informe seu usuário e senha
6. Pronto! Uma nova unidade aparecerá no seu computador

### No macOS

1. No Finder, clique em **Ir > Conectar ao Servidor**
2. Digite: `https://<seu-endereco>/webdav/`
3. Informe seu usuário e senha

### No Linux

- (Ubuntu): `davs://<seu-endereco>/webdav/`
- (KDE): `webdav://<seu-endereco>/webdav/`

---

## Streaming de Mídia

O mobNAS funciona como um servidor de mídia pessoal.

### Assistir Vídeos

- Formatos: MP4, MKV, MOV, WEBM
- Clique no vídeo no gerenciador de arquivos
- Ele será reproduzido diretamente no navegador ou no app
- Funciona mesmo em arquivos grandes

### Ouvir Música

- Formatos: MP3, FLAC, AAC, WAV
- Clique na música para ouvir

---

### Monitoramento do Túnel

No Painel do app, você vê:
- ✅ Se o túnel está conectado
- 🌐 A URL pública ativa
- 🔄 Reinício automático se cair

---

## Modo NAS (24/7)

O Modo NAS foi feito para quem quer deixar o servidor rodando o tempo todo sem se preocupar com a bateria do dispositivo, operando em carga máxima 24 horas por dia 7 dias por semana, usufruindo de todo o potencial do aparelho sem perda de desempenho durante operações de upload, download e consultas de arquivos.

### O que ele faz?

- Mantém o servidor ligado mesmo com o app em segundo plano
- Impede que o celular entre em modo de suspensão
- Mostra uma notificação persistente: "NAS Droid Online — Servidor Ativo"

### Como ativar

1. Vá em **Ajustes**
2. Ative **Modo NAS**
3. Permita que o app ignore a otimização de bateria (o sistema vai pedir)

### Inicialização Automática

Se o Modo NAS estiver ativo, o servidor liga automaticamente quando:
- Você abre o aplicativo
- O celular é reiniciado (Boot Receiver)

---

## Monitoramento

O sistema monitora a saúde do seu dispositivo em tempo real.

### Métricas Coletadas

| Métrica | Descrição |
|---|---|
| 🖥️ CPU | Uso do processador |
| 🌡️ Temperatura | Temperatura do dispositivo |
| 💾 RAM | Memória disponível |
| 📀 Armazenamento | Espaço usado e livre |
| 🔋 Bateria | Nível e se está carregando |
| 👥 Clientes | Dispositivos conectados |
| ⬆️⬇️ Atividade | Uploads e downloads ativos |

---

## Backup

Você pode fazer backup dos seus arquivos:

1. Vá em **Ajustes > Backup**
2. Escolha:
   - **Fazer backup agora**: Cria um arquivo ZIP imediatamente
   - **Agendar backup**: Diário, semanal ou mensal

---

## Perguntas Frequentes

### Preciso de um celular potente?

Não. Qualquer Android com Android 9 (API 26) ou superior funciona. Um celular antigo que você não usa mais é perfeito.

### O consumo de bateria é alto?

O Modo NAS mantém o dispositivo acordado, então o consumo é maior que o normal. Outra questão importante é sobre o uso de armazenamentos externos como SSD's, HD's e pendrives, conectá-los através de adaptadores OTG pode elevar o consumo de bateria. Recomenda-se o uso de cartões de memória de séries de alta performance caso o dispositivo possua compatibilidade. 

Você pode também experimentar a remoção da bateria do dispositivo no caso de smartphones ou tablets. Na internet é possível encontrar tutoriais que auxiliam com esses experimentos. ISSO É POR SUA PRÓPRIA CONTA E RISCO.

### O mobNAS É seguro?

Sim. O acesso requer login e senha.

Criptografia de senhas: utilizamos PBKDF2 com salt para armazenamento seguro de senhas.

Autenticação JWT: tokens JSON Web Token para sessões seguras com validade de 24 horas.

Refresh tokens: para renovação segura de sessões sem reenvio de credenciais.

Rate limiting: limitação de tentativas de login para prevenção de ataques de força bruta.

Bloqueio por tentativas: após 5 tentativas consecutivas de login com falha, o usuário é bloqueado por 15 minutos.

Registro de tentativas: todas as tentativas de login (sucesso e falha) são registradas com IP, data e dispositivo.

HTTPS recomendado: o acesso remoto via Cloudflare Tunnel utiliza criptografia TLS.

### Posso acessar de qualquer lugar?

Sim, com o Cloudflare Tunnel configurado, você acessa de qualquer lugar com internet.

### Meus arquivos ficam disponíveis pra acessar de qualquer lugar?

Sim. Os arquivos permanecem físicos no seu dispositivo Android. O Cloudflare apenas cria o túnel de acesso, seus arquivos não são armazenados fora do dispositivo com o mobNAS instalado.

### Funciona com qualquer operadora de internet?

Sim. O aplicativo não depende de configurações da operadora.

### Quantos usuários posso ter?

Não há limite. Você pode cadastrar quantos usuários quiser e definir permissões individuais.

### Posso conectar meu videogame?

O NAS é acessível via navegador, então sim, desde que o videogame tenha um navegador. Para Smart TVs, recomendamos o WebDAV ou acesso pelo navegador.

---

## Suporte e Comunidade

### Recursos

- 📖 **Este documento** — guia completo de uso
- 🐛 **Relatar problemas** — encaminhe um email com sua sugestão ou problema encontrado para contato@wbytesistemas.com.br

### Sugestões

Tem uma ideia para melhorar o mobNAS? Fique à vontade para contribuir com sugestões.

---

*Obrigado por usar o mobNAS!*

*Documentação atualizada em Julho de 2026.*
