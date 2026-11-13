<div align="center">

<img src="https://ibseren.com/marca/ibseren-lockup-2400.png" alt="IBSEREN Forense" width="480"/>

<br/>

**Suíte de Perícia Digital Móvel**

<br/>

[![Versão](https://img.shields.io/badge/versão-8.9.6-1189E0?style=flat-square&labelColor=050A14)](https://github.com/resenhacyber/IbserenForense-Core/releases/latest)
[![Plataforma](https://img.shields.io/badge/plataforma-Windows%2010%2F11-1189E0?style=flat-square&labelColor=050A14&logo=windows&logoColor=white)](https://github.com/resenhacyber/IbserenForense-Core/releases/latest)
[![Uso](https://img.shields.io/badge/uso-perícia%20autorizada-FFB020?style=flat-square&labelColor=050A14)](https://www.ibseren.com)
[![Site](https://img.shields.io/badge/site-ibseren.com-00BCF2?style=flat-square&labelColor=050A14)](https://www.ibseren.com)

> Desenvolvida por **ResenhaCyber** · Claudio Silva &nbsp;×&nbsp; **Investigareee** · Ibsen Maciel
>
> *Repositório institucional de apresentação. O código-fonte é proprietário e mantido em repositório privado.*

</div>

---

## ⬇️ Download — v8.9.6

<div align="center">

**[📦 Ibseren-Forense-Setup-v8.9.6.exe](https://github.com/resenhacyber/IbserenForense-Core/releases/latest)**

</div>

| Campo | Valor |
|---|---|
| Versão | **8.9.6** |
| Arquivo | `Ibseren-Forense-Setup-v8.9.6.exe` |
| Tamanho | 306 MB |
| SHA-256 | `9dbcc3929e0e42e451d40a0d7b01ac241492cf15b942dffc575980ded027d8ae` |
| Sistema | Windows 10 / 11 (64-bit) |

### Passos de instalação

1. Baixe o instalador no link acima.
2. Execute `Ibseren-Forense-Setup-v8.9.6.exe` — confirme o UAC se solicitado.
3. Siga o assistente em Português do Brasil.
4. Opcionalmente crie atalho na Área de Trabalho.
5. Clique em **Concluir** para abrir o Ibseren Forense.

> **Verificação de integridade:**
> ```powershell
> Get-FileHash .\Ibseren-Forense-Setup-v8.9.6.exe -Algorithm SHA256
> ```
> Compare o hash com o SHA-256 acima.

### Requisitos

| Componente | Requisito |
|---|---|
| Sistema Operacional | Windows 10 / 11 (64-bit) |
| Memória RAM | 4 GB mínimo (8 GB recomendado) |
| Espaço em disco | 1 GB para instalação + espaço para evidências |
| Android | Driver ADB instalado automaticamente |
| iOS | Apple Mobile Device Service (iTunes / Apple Devices) ou driver embutido iniciado automaticamente |

### Novidades da v8.9.6

- **Olho de Deus iOS** — recuperação de mídias View Once do WhatsApp em backups iTunes
- **Driver Apple embutido** — inicia `usbmuxd` automaticamente sem necessidade de instalação
- **Installer profissional** — setup.exe com assistente, atalhos e desinstalador

> Para obter sua licença de uso, acesse o site oficial: **[www.ibseren.com](https://www.ibseren.com)**

---

## Nossa História

O **Ibseren Forense** nasceu do encontro de dois mundos que raramente se encontram em uma mesma ferramenta: a **perícia criminal oficial** e a **engenharia ofensiva de segurança**.

De um lado, anos de atuação em investigações reais de crimes cibernéticos no Estado do Pará — onde cada caso trazia o mesmo desafio: dispositivos cada vez mais protegidos, evidências cada vez mais difíceis de alcançar, e soluções comerciais cada vez mais distantes da realidade operacional das perícias brasileiras. Do outro, uma sólida trajetória em pesquisa de vulnerabilidades e desenvolvimento full stack, com a vivência prática de quem entende como os sistemas são atacados — e, portanto, como podem ser examinados em profundidade.

Dessa união entre a **experiência de quem está na linha de frente das investigações** e o **conhecimento técnico de quem domina a arquitetura das plataformas móveis**, surgiu uma suíte construída sob medida para o cenário real da perícia nacional: robusta nos fundamentos forenses — cadeia de custódia, integridade e rastreabilidade — e eficaz nos cenários mais adversos de aquisição.

O nome **Ibseren** carrega essa parceria: a junção de **Investigareee** e **ResenhaCyber** em um único propósito — colocar tecnologia de ponta a serviço da justiça.

---

## Autores

### 🕵️ Ibsen Rodrigues Maciel — Investigareee

Perito Criminal Oficial em Forense Computacional da **Polícia Científica do Estado do Pará**, atuando também vinculado à **Polícia Civil do Pará (DECCC)**. Reconhecido nacionalmente por sua atuação em investigações de crimes cibernéticos e em **extração avançada de dados** de dispositivos móveis. Leva à suíte a visão de quem vivencia diariamente os desafios reais da perícia em campo.

### 💻 Claudio Silva — ResenhaCyber

Bug Hunter focado em **Desenvolvimento Full Stack** e na identificação de vulnerabilidades reais em aplicações, APIs e ambientes cloud, com análise técnica profunda e visão prática de ataque e defesa. Leva à suíte a engenharia capaz de transformar desafios de acesso em soluções de aquisição.

---

## Visão Geral

O **Ibseren Forense** é uma suíte profissional de perícia digital especializada na aquisição, análise e documentação de evidências provenientes de dispositivos móveis **Android** e **iOS**. Projetada para uso em perícias oficialmente autorizadas, a ferramenta cobre desde o reconhecimento do dispositivo até a emissão do relatório pericial final, com cadeia de custódia, integridade criptográfica e rastreabilidade completas de todas as operações.

A suíte atende aos mais diversos cenários encontrados em campo — de dispositivos sem qualquer modificação a aparelhos bloqueados ou com restrições de acesso — oferecendo múltiplos níveis de aquisição, do lógico ao físico, sempre com registro auditável de cada etapa.

---

## Plataformas e Cobertura

| Plataforma | Cobertura |
|---|---|
| **Android** | Aquisição lógica, avançada e física, incluindo dispositivos sem root, sem desbloqueio de tela e versões recentes do sistema |
| **iOS (iPhone / iPad)** | Detecção, backup iTunes, análise iLEAPP (100+ artefatos), screenshot ao vivo, inventário de aplicativos e recuperação de mídias View Once |
| **Plataformas Qualcomm** | Suporte a aquisição física (imagem completa do armazenamento) |
| **Plataformas MediaTek** | Suporte a aquisição física (imagem completa do armazenamento) |

---

## Módulos da Suíte

A suíte é organizada em módulos independentes e integrados, agrupados por fase do fluxo pericial: **Reconhecimento**, **Aquisição**, **Análise** e **Relatório**.

---

### 1. Reconhecimento

#### 🎯 Diagnóstico e Detecção de Dispositivos

Reconhecimento automatizado de qualquer dispositivo conectado, Android ou Apple, com mapeamento completo do cenário de acesso disponível.

**Capacidades:**
- Detecção unificada de dispositivos Android e iOS em um único ponto de entrada.
- Identificação de fabricante, modelo, versão do sistema operacional e estado de segurança do aparelho.
- Mapeamento dos vetores de aquisição disponíveis para o dispositivo em questão.
- Recomendação automática da estratégia de aquisição mais adequada ao cenário identificado.
- Inventário de aplicativos instalados, com destaque para mensageiros suportados e indicadores de interesse forense.

---

### 2. Aquisição

#### 📥 Aquisição Lógica Android

Aquisição completa de dispositivos Android sem necessidade de root ou modificação do aparelho.

**Capacidades:**
- Cópia integral do armazenamento compartilhado (fotos, vídeos, áudios, documentos e mídias de aplicativos), com preservação da estrutura original de diretórios.
- Coleta de dados lógicos do sistema: SMS, MMS, registro de chamadas e contatos.
- Identificação automática de áreas protegidas do sistema, com registro formal dos itens não acessíveis.
- Extração de aplicativos instalados para análise posterior.
- Coleta direcionada de dados públicos dos principais aplicativos de interesse forense.
- Continuidade de operação em conexões instáveis, com recuperação automática da sessão de aquisição.
- Registro de integridade (SHA-256) de todos os artefatos coletados.

#### 📦 Aquisição Estendida de Aplicativos

Modalidade ampliada de coleta que expande a cobertura de dados de aplicativos de interesse quando o dispositivo oferece condições de acesso.

**Capacidades:**
- Cobertura dos principais mensageiros e aplicativos de comunicação corporativa.
- Preservação integral dos dados coletados com hash de integridade individual.
- Registro detalhado, por aplicativo, do que foi coletado, ignorado ou indisponível.
- Execução não intrusiva, sem alteração permanente do dispositivo.

#### 🔑 Extração Root

Aquisição completa em dispositivos com acesso privilegiado já existente.

**Capacidades:**
- Coleta recursiva de bancos de dados, preferências e artefatos internos dos aplicativos.
- Verificação de integridade dos arquivos no próprio dispositivo, antes da transferência.
- Custódia separada de chaves criptográficas sensíveis.

#### 💾 Backup ADB

Processamento forense de backups obtidos pela interface de depuração do Android.

**Capacidades:**
- Backup completo do dispositivo ou direcionado a aplicativos específicos.
- Processamento e extração do conteúdo de arquivos de backup.
- Suporte a backups protegidos por senha.
- Recuperação parcial de conteúdo mesmo em backups danificados ou incompletos.

#### 🛡️ Vetores de Acesso Alternativos

Conjunto de estratégias complementares para cenários em que os métodos convencionais não estão disponíveis.

**Capacidades:**
- Vetores de compatibilidade para habilitar a aquisição em aplicativos que restringem o acesso aos próprios dados.
- Avaliação automática do vetor mais adequado com base no diagnóstico do dispositivo.
- Processamento de backups de nuvem previamente obtidos por meios autorizados.

#### 🔐 Obtenção de Chave de Criptografia WhatsApp

Obtenção assistida da chave de criptografia de backups do WhatsApp em cenários autorizados.

**Capacidades:**
- Processo assistido e auditável, com múltiplas estratégias de validação.
- Compatibilidade com versões recentes do Android, incluindo as gerações mais atuais do sistema.
- Validação criptográfica da chave obtida antes do uso na decifração.
- Registro formal do método utilizado e do resultado na documentação do caso.

#### 💽 Aquisição Física — Qualcomm e MediaTek

Aquisição de baixo nível para obtenção da imagem completa do armazenamento do dispositivo.

**Capacidades:**
- Imagem forense completa (full file system), incluindo áreas não acessíveis por métodos lógicos.
- Aplicável a dispositivos bloqueados e sem acesso ao sistema operacional, em cenários devidamente autorizados.
- Cobertura das duas principais plataformas de chipset do mercado Android.
- Preservação de partições e estruturas brutas para análise aprofundada.

#### ⚡ Extração em Tempo de Execução

Obtenção de chaves criptográficas e artefatos sensíveis diretamente de aplicativos em execução.

**Capacidades:**
- Captura de chaves e dados protegidos no contexto de execução do próprio aplicativo.
- Aplicável a aplicativos cujos dados em repouso são inacessíveis por outros vetores.
- Registro auditável de todo o processo de captura.

#### 🖥️ Captura Avançada de Interface (Advanced Logical)

Registro forense de conversas e conteúdo diretamente da interface do aplicativo, quando o banco de dados está inacessível.

**Capacidades:**
- Documentação integral de conversas em aplicativos com proteção reforçada de dados.
- Preservação do conteúdo em imagem e em texto pesquisável.
- Aplicável a mensageiros e plataformas corporativas sem vetor direto de extração.

#### 🍏 Aquisição iOS — Fluxo Completo

Suporte dedicado a dispositivos Apple, com fluxo pericial completo integrado em um único ambiente.

**Fluxo de trabalho:**

| Etapa | Função | Descrição |
|---|---|---|
| 1 | **Detectar dispositivo** | Identifica iPhone/iPad via USB — exibe UDID, modelo e versão do iOS |
| 2 | **Informações completas** | IMEI, ICCID, número de série, capacidade de armazenamento |
| 3 | **Backup iTunes** | Backup lógico completo via protocolo nativo Apple; fallback automático para `idevicebackup2` |
| 4 | **Análise iLEAPP** | Processa o backup com 100+ parsers de artefatos — relatório HTML gerado automaticamente |
| 5 | **Backup + iLEAPP** | Executa as etapas 3 e 4 em sequência com um único clique |
| 6 | **Screenshot ao vivo** | Captura a tela atual do dispositivo durante a perícia |
| 7 | **Inventário de apps** | Lista todos os aplicativos instalados com bundle ID, nome e versão — salvo em JSON |

**Artefatos cobertos pelo iLEAPP (100+ categorias):**

> Histórico de localização GPS · Saúde e atividade física · Histórico do Safari · Notas · Calendário e Lembretes · Screen Time · Uso de aplicativos · Notificações · Redes Wi-Fi conhecidas · Contas configuradas · Voicemail · Fotos (metadados EXIF) · Registros de chamadas · SMS e iMessage · Contatos · e muito mais.

**Binários embutidos (sem dependências externas):**
- `iLEAPP` — engine de análise de artefatos iOS
- `idevicebackup2` — backup iTunes via libimobiledevice
- `idevicescreenshot` — captura de tela ao vivo
- `ideviceinstaller` — inventário de aplicativos instalados

---

### 3. Análise

#### 🔓 Decifrador WhatsApp

Decriptografia de bancos de dados e mídias protegidos do WhatsApp.

**Capacidades:**
- Suporte aos formatos de criptografia **crypt12**, **crypt14** e **crypt15**.
- Decifração de mídias associadas às conversas.
- Validação de integridade criptográfica do conteúdo decifrado.
- Recuperação parcial de arquivos danificados.
- Varredura de estruturas residuais do banco para recuperação de artefatos.

#### 👁️ Olho de Deus — Android

Recuperação de mídias de visualização única (View Once) do WhatsApp em dispositivos Android.

**Capacidades:**
- Identificação de registros de conteúdo efêmero nas bases do aplicativo.
- Busca de chave criptográfica em 10+ tabelas alternativas do schema Android.
- Varredura WAL/freelist do banco para recuperação de chaves residuais.
- Recuperação da mídia associada quando preservada de forma residual no dispositivo.
- Documentação individual de cada item recuperado, com metadados e hash de integridade.
- Relatório visual dedicado, autocontido e portátil.

#### 👁️ Olho de Deus iOS — *Novo em v8.9.6*

Recuperação de mídias de visualização única (View Once) do WhatsApp em iPhones, operando sobre o backup iTunes. Equivalente completo do Olho de Deus Android, adaptado ao schema Core Data do iOS.

**Fluxo de uso:**
1. Realize o backup iTunes do iPhone (não criptografado)
2. Na aba iOS → seção *Olho de Deus iOS*, informe a pasta do backup
3. Marque *Apenas View Once* para filtrar somente mensagens efêmeras
4. Clique em 👁 Olho de Deus iOS

**Capacidades:**
- **Recuperação local do backup iTunes via Manifest.db** — localiza e decifra mídias diretamente do backup, sem necessidade de internet ou CDN.
- **Download e decifração via CDN WhatsApp** — fallback automático para mídias não presentes no backup local.
- **Busca de chave alternativa** — vasculha 7+ tabelas do schema iOS (`ZWAMESSAGE`, `ZWAEPHEMERAL`, `ZWAMEDIAKEYS`, `ZWAMESSAGESECRET`, `ZWAVIEWONCE`) quando a chave primária está ausente.
- **Varredura WAL/freelist** do `ChatStorage.sqlite` para recuperação de chaves residuais em áreas deletadas.
- **Relatório HTML profissional** com galeria visual, thumbnails embutidos em base64, SHA-256 por item e cadeia de custódia completa.

#### 🔍 Análise Offline

Exame aprofundado de bancos de dados já extraídos, independentemente do dispositivo.

**Capacidades:**
- Leitura adaptativa de bancos SQLite, mesmo com estrutura desconhecida.
- Recuperação de registros excluídos logicamente pelo aplicativo.
- Reconstrução de linha do tempo de mensagens e eventos.
- Análise de estruturas internas do banco em busca de artefatos residuais.

#### 📊 Pós-Processamento Android — ALEAPP

Integração com a engine **ALEAPP** (Android Logs Events And Protobuf Parser) para análise automatizada dos dados adquiridos.

**Capacidades:**
- Parsing de centenas de tipos de artefatos do sistema Android e de aplicativos.
- Geração de relatórios estruturados a partir dos dados brutos da aquisição.
- Execução como etapa opcional integrada ao fluxo de aquisição.

#### 🍏 Pós-Processamento iOS — iLEAPP

Integração com a engine **iLEAPP** (iOS Logs Events And Protobuf Parser) para análise forense completa de backups iTunes.

**Capacidades:**
- Mais de 100 parsers de artefatos nativos do iOS — Health, GPS, Safari, Notes, Screen Time, App Usage e muito mais.
- Relatório HTML gerado automaticamente, pronto para anexar ao laudo pericial.
- Funciona sobre qualquer backup iTunes obtido pela suíte ou por terceiros.
- Motor embutido no executável — sem instalação adicional.

#### 📋 Inventário Forense

Catalogação completa do estado do dispositivo para documentação pericial.

**Capacidades:**
- Relação de todos os aplicativos instalados e permissões críticas concedidas.
- Identificação de aplicativos potencialmente suspeitos.
- Exportação do inventário em formato adequado ao relatório pericial.

---

### 4. Relatório e Cadeia de Custódia

#### 📄 Relatório Pericial Unificado

Consolidação de todas as extrações do caso em um relatório profissional, no padrão das principais suítes comerciais do mercado.

**Capacidades:**
- Relatório único em HTML, com conteúdo real e legível: mensagens, chamadas, conversas e mídias.
- Sumário executivo com dados do caso e do responsável técnico.
- Seções dedicadas por aplicativo e por fonte de evidência.
- Linha do tempo de eventos forenses.
- Anexação de mídias recuperadas e galeria visual.
- Hash de integridade do próprio relatório e página de assinatura.

#### 📜 Log Auditável

Registro contínuo e exportável de todas as operações executadas pela ferramenta.

**Capacidades:**
- Console em tempo real com níveis de severidade e filtragem.
- Exportação do histórico completo da sessão para documentação do caso.

#### 🧾 Cadeia de Custódia

- Hash SHA-256 dos artefatos coletados, com verificação de integridade entre origem e destino.
- Registro de data e hora (UTC) de cada operação.
- Custódia segregada de chaves criptográficas.
- Manifesto de integridade acompanhando cada aquisição.

---

## Aplicativos Suportados

| Mensageria | Redes Sociais | Corporativo |
|---|---|---|
| WhatsApp / WhatsApp Business | Instagram | Microsoft Teams |
| Telegram / Telegram X | Facebook | Skype |
| Signal | Messenger | |
| Viber | Snapchat | |
| Line | Discord | |

---

## Histórico de Versões

| Versão | Destaques |
|---|---|
| **v8.9.6** | Olho de Deus iOS: recuperação de View Once via backup iTunes, busca de chave alternativa, WAL scan e relatório profissional |
| **v8.9.5** | Fluxo iOS completo: iLEAPP + idevicebackup2 + screenshot + inventário de apps — tudo embutido |
| **v8.9.3** | Sistema de licenciamento online (IBSRN-\*) com validação por API |
| **v8.9.x** | Módulos Android: CopyAll, Downgrade APK, decifração crypt12/14/15, View Once, Backup iOS |

---

## Licenciamento

O Ibseren Forense é distribuído sob **licenciamento comercial**, com ativação por chave online e validade configurável. A licença é vinculada à máquina do perito e validada contra o servidor de licenças no momento da abertura.

Para informações sobre aquisição de licenças, acesse **[www.ibseren.com](https://www.ibseren.com)**.

---

## Uso Autorizado

> ⚖️ **Aviso legal:** o Ibseren Forense destina-se exclusivamente a perícias digitais formalmente autorizadas — por ordem judicial, consentimento do titular ou outra base legal aplicável. O uso da ferramenta fora dessas hipóteses é de inteira responsabilidade do operador.

---

<div align="center">

<img src="https://ibseren.com/marca/ibseren-simbolo.svg" alt="IBSEREN" width="48"/>

**IBSEREN** — ResenhaCyber × Investigareee

[www.ibseren.com](https://www.ibseren.com) · Use com responsabilidade e dentro da legalidade.

</div>
