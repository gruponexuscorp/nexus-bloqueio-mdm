<div align="center">

# 🔒 Nexus: Bloqueio MDM

![Platform](https://img.shields.io/badge/Android-10%2B-3ddc84?logo=android&logoColor=white)
![Type](https://img.shields.io/badge/Type-MDM%20%2F%20Kiosk-4c9fe0)
![Version](https://img.shields.io/badge/Version-8.0-blue)

**[🇺🇸 English](#-english) · [🇧🇷 Português](#-português)**

</div>

---

<a name="-english"></a>

## 🇺🇸 English

**Turn corporate phones into restricted, secure, managed devices.**

### 📱 What it is

**Nexus: Bloqueio MDM** is a device management app (MDM / kiosk mode) for Android. It turns an ordinary phone into a **controlled corporate device**: only approved apps are available, uninstalling and system changes are blocked, and the user is clearly informed that the device is for corporate use and may be monitored.

Built for companies that **hand phones to employees** and need to make sure the device is used only for work.

### 🎯 Who it's for

- **Service posts, front desks and reception** — a fixed device for specific tasks
- **Field teams, patrol and security** — a phone with only the essentials (patrol, time clock, messaging)
- **Corporate phone fleets** — many standardized, locked devices
- **Managers** who need to prevent misuse, app installs and setting changes

### ✨ What it does

- 🔒 **Kiosk mode** — only the allowed apps show on screen
- 🚫 **Blocks uninstalling** the app itself and the factory reset by the user
- 📷 **Stamped camera** (date, time and GPS) set as the default
- 🖼️ **Fixed notice** "corporate, managed device" on both the home screen **and** the lock screen
- 🔑 **PIN-protected admin panel**
- ⚙️ **Choose the allowed apps** right from the panel
- 📡 **Bulk install via QR Code** for new devices

### 🛡️ Security

- **Device owner** — the highest level of control Android offers
- **Admin PIN** stored with a **PBKDF2** hash (never in plain text)
- **Signature checksum verification** on QR install — the device only accepts the original app
- **USB debugging blocked** after setup, closing the back door

### 💻 Requirements

- Android **10 (API 29)** or higher
- **Cable install:** a computer with ADB
- **QR install:** a factory-reset device

### ⬇️ Download

➡️ **Get the latest version from the [Releases](../../releases/latest) tab.**

The `Bloqueio-final.apk` file downloads directly — just click it.

### 🚀 How to install

There are two paths. Pick the one that fits the device.

**A) Phone already in use — by cable (no wipe)**

Best when **the post can't be left without the device**. Keeps the phone's apps and files.

1. Enable **USB debugging** on the phone
2. Remove the Google accounts from the device (required by Android)
3. Connect it to the computer and run the activation command
4. Done — the lock is applied in a few minutes

> Detailed steps live in the **admin guide** (internal use).

**B) New devices or in bulk — by QR Code**

Best to **set up several devices from scratch** at once.

1. Factory-reset phone → **tap 6 times** on the welcome screen
2. Connect to **Wi-Fi**
3. **Scan the provisioning QR**
4. The device downloads, installs and locks **itself**

### ⚖️ Legal notice

A tool meant for **company- or organization-owned devices**, for legitimate corporate use and with the **users' awareness**. The device permanently displays the notice that it is managed and may be monitored.

---

<a name="-português"></a>

## 🇧🇷 Português

**Transforme celulares corporativos em aparelhos de uso restrito, seguro e gerenciado.**

### 📱 O que é

O **Nexus: Bloqueio MDM** é um aplicativo de gerenciamento de dispositivos (MDM / modo quiosque) para Android. Ele transforma um celular comum em um **aparelho corporativo controlado**: libera apenas os aplicativos autorizados, impede desinstalação e alterações no sistema, e deixa claro ao usuário que o aparelho é de uso corporativo e monitorado.

Feito para empresas que **fornecem celulares a funcionários** e precisam garantir que o aparelho seja usado apenas para o trabalho.

### 🎯 Para quem é

- **Postos de serviço, portarias e recepções** — aparelho fixo para tarefas específicas
- **Equipes de campo, rondas e vigilância** — celular só com o essencial (rondas, ponto, comunicação)
- **Frotas de celulares corporativos** — vários aparelhos padronizados e bloqueados
- **Gestores** que precisam impedir uso indevido, instalação de apps e mudança de configurações

### ✨ O que ele faz

- 🔒 **Modo quiosque** — só os aplicativos liberados aparecem na tela
- 🚫 **Impede desinstalação** do próprio app e o reset de fábrica pelo usuário
- 📷 **Câmera com carimbo** de data, hora e GPS definida como padrão
- 🖼️ **Aviso fixo** de "aparelho de uso corporativo e gerenciado" na tela inicial **e** na tela de bloqueio
- 🔑 **Painel de administrador protegido por PIN**
- ⚙️ **Escolha dos apps liberados** direto no painel
- 📡 **Instalação em lote por QR Code** para aparelhos novos

### 🛡️ Segurança

- **Administrador do dispositivo (device owner)** — o nível máximo de controle que o Android oferece
- **PIN de administrador** guardado com hash **PBKDF2** (nunca em texto puro)
- **Verificação por checksum de assinatura** na instalação por QR — o aparelho só aceita o app original
- **Depuração USB bloqueada** após a configuração, fechando a porta dos fundos

### 💻 Requisitos

- Android **10 (API 29)** ou superior
- **Instalação por cabo:** um computador com ADB
- **Instalação por QR:** aparelho de fábrica (zerado)

### ⬇️ Download

➡️ **Baixe a versão mais recente na aba [Releases](../../releases/latest).**

O arquivo `Bloqueio-final.apk` baixa direto, é só clicar.

### 🚀 Como instalar

Existem dois caminhos. Escolha conforme a situação do aparelho.

**A) Celular já em uso — pelo cabo (sem formatar)**

Ideal quando **não dá para deixar o posto sem o aparelho**. Mantém os apps e arquivos do celular.

1. Ative a **Depuração USB** no celular
2. Remova as contas Google do aparelho (passo exigido pelo Android)
3. Conecte ao computador e rode o comando de ativação
4. Pronto — o bloqueio é aplicado em poucos minutos

> As instruções detalhadas ficam no **guia do administrador** (uso interno).

**B) Aparelhos novos ou em lote — por QR Code**

Ideal para **configurar vários aparelhos do zero** de uma vez.

1. Celular de fábrica → **toque 6 vezes** na tela de boas-vindas
2. Conecte ao **Wi-Fi**
3. **Escaneie o QR** de provisionamento
4. O aparelho baixa, instala e se bloqueia **sozinho**

### ⚖️ Aviso legal

Ferramenta destinada a **aparelhos de propriedade da empresa ou organização**, para uso corporativo legítimo e com **ciência dos usuários**. O aparelho exibe, de forma permanente, o aviso de que é gerenciado e pode ser monitorado.

---

<div align="center">
<sub>Nexus: Bloqueio MDM — corporate phone lockdown & management / solução de bloqueio e gerenciamento para celulares corporativos.</sub>
</div>
