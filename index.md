# Política de Privacidade — Zé-lionário

**Última atualização:** 5 de maio de 2026
**Controlador:** Daniel Filho (`danielfilho8@gmail.com`)
**Aplicativo:** Zé-lionário (`br.com.zelionario.game`)

Este documento descreve como o aplicativo Zé-lionário (doravante "App") coleta, utiliza, compartilha e protege seus dados, em conformidade com a **Lei Geral de Proteção de Dados (LGPD — Lei nº 13.709/2018)**, requisitos do Google Play, Firebase, AdMob e Google Play Billing.

---

## 1. Dados que coletamos

### 1.1 Dados de identificação anônima
Ao abrir o App pela primeira vez, geramos automaticamente um identificador único anônimo (UID Firebase). Esse UID **não é vinculado a sua identidade real** e serve apenas para sincronizar seu progresso de jogo entre dispositivos.

### 1.2 Dados de conta Google (opcional)
Caso você opte por **conectar uma conta Google** dentro do App (Configurações → Conta → Conectar com Google), coletamos:
- Endereço de e-mail.
- Nome e foto de perfil públicos.
- ID Google.

Esses dados são usados exclusivamente para autenticação e sincronização do save entre dispositivos. Você pode desconectar a qualquer momento (Configurações → Conta → Sair).

### 1.3 Dados de progresso do jogo
Armazenamos seu progresso de jogo (cash, fontes de renda, conquistas, prestige, configurações) em:
- **Localmente:** banco de dados Hive no seu dispositivo.
- **Nuvem (Firebase Firestore):** vinculado ao seu UID, somente para permitir sincronização entre dispositivos.

### 1.4 Dados de uso e analytics
Utilizamos **Firebase Analytics** para coletar dados anônimos sobre o uso do App:
- Eventos do jogo (compra de tier, prestige, ads vistos, conquistas desbloqueadas).
- Tempo de sessão, telas acessadas.
- Tipo e modelo do dispositivo, versão do sistema operacional.
- Idioma e país (aproximado).

Esses dados são **agregados e anônimos**, não permitem identificação pessoal direta, e servem para melhorarmos a experiência do App.

### 1.5 Dados de publicidade
O App exibe anúncios via **Google AdMob**, que pode coletar:
- Identificador de Publicidade do Android (Advertising ID).
- Dados aproximados de localização (baseados em IP).

A AdMob possui sua própria política: <https://policies.google.com/technologies/ads>. Você pode redefinir ou desativar o Advertising ID nas configurações do seu dispositivo Android (Configurações → Google → Anúncios).

### 1.6 Dados de compras
Compras dentro do App (IAP) são processadas pelo **Google Play Billing**. Nós **não armazenamos** dados de cartão de crédito ou método de pagamento. Apenas registramos:
- Identificador da compra (token).
- SKU do produto adquirido.
- Status (concluída, restaurada, reembolsada).

---

## 2. Como usamos seus dados

| Finalidade | Dados utilizados |
|---|---|
| Autenticar e identificar você no jogo | UID anônimo, conta Google (se conectada) |
| Sincronizar progresso entre dispositivos | UID, dados de progresso |
| Personalizar experiência (modo noturno, volume) | Configurações locais |
| Exibir anúncios relevantes | Advertising ID (gerenciado pela AdMob) |
| Validar e entregar compras dentro do app | Token de compra, SKU |
| Melhorar o App (analytics agregado) | Eventos de uso anonimizados |
| Detectar e prevenir fraudes | Logs de autenticação |

**Não usamos seus dados para:**
- Vender a terceiros para fins comerciais.
- Marketing por e-mail (não enviamos e-mails).
- Perfilamento sensível (saúde, religião, política, orientação sexual).

---

## 3. Compartilhamento com terceiros

Os seguintes serviços processam dados em nosso nome (operadores, conforme LGPD):

| Serviço | Finalidade | Política |
|---|---|---|
| **Google Firebase** (Auth, Firestore, RemoteConfig, Analytics) | Autenticação, save em nuvem, configuração remota | <https://firebase.google.com/support/privacy> |
| **Google AdMob** | Exibição de anúncios | <https://policies.google.com/technologies/ads> |
| **Google Play Billing** | Processamento de compras | <https://policies.google.com/privacy> |

Não compartilhamos dados com terceiros não listados acima.

---

## 4. Retenção e exclusão

- **Dados locais:** ficam no seu dispositivo enquanto o App estiver instalado. São apagados ao desinstalar.
- **Dados na nuvem:** ficam vinculados ao seu UID enquanto sua conta existir. Você pode solicitar a exclusão a qualquer momento (ver seção 6).
- **Logs de analytics:** retidos por até 14 meses, conforme padrão do Firebase Analytics.

---

## 5. Segurança

- Comunicação com servidores via **HTTPS/TLS**.
- Banco Firestore protegido por **Security Rules** que garantem que apenas você acessa seus dados (via UID).
- Compras validadas pelo Google Play Billing (não armazenamos dados financeiros).

Apesar dessas medidas, nenhum sistema é 100% seguro. Em caso de incidente que afete dados pessoais, notificaremos os usuários afetados conforme a LGPD.

---

## 6. Seus direitos (LGPD)

Você tem direito a:
- **Confirmar** se tratamos seus dados.
- **Acessar** os dados que temos sobre você.
- **Corrigir** dados incompletos, inexatos ou desatualizados.
- **Anonimizar, bloquear ou excluir** dados desnecessários ou tratados em desconformidade.
- **Portabilidade** dos dados a outro fornecedor.
- **Revogar consentimento** a qualquer momento.

Para exercer qualquer direito, envie um e-mail para **danielfilho8@gmail.com** com o assunto `[Zé-lionário] Solicitação LGPD` e descreva o pedido. Responderemos em até 15 dias.

---

## 7. Crianças

O App **não é direcionado a menores de 13 anos**. Não coletamos intencionalmente dados de crianças. Caso identifiquemos que coletamos dados de uma criança sem o consentimento dos pais ou responsáveis, excluiremos imediatamente.

---

## 8. Alterações nesta política

Podemos atualizar esta política a qualquer momento. Mudanças significativas serão comunicadas dentro do App. A versão mais atual estará sempre disponível em:

`https://<seu-usuario>.github.io/zelionario-policy/`

(O link acima será atualizado após a publicação do GitHub Pages.)

---

## 9. Contato

Dúvidas, reclamações ou solicitações:

**Daniel Filho**
E-mail: **danielfilho8@gmail.com**

---

*Esta política foi escrita em conformidade com a LGPD (Brasil), GDPR (UE — quando aplicável a usuários europeus), e diretrizes do Google Play e Firebase.*
