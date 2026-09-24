# R.R Estética & Massoterapia - Beatriz Ramos

Website institucional de estética e massoterapia com atendimento domiciliar exclusivo na Zona Sul de São Paulo, integrando sistema de agendamento online inteligente conectado a CRM Google Sheets / Google Apps Script e WhatsApp.

---

## 🌟 Identidade Visual & Proposta
- **Profissional:** Beatriz Ramos
- **Marca:** R.R Estética & Massoterapia
- **Lema:** *Cuidar • Renovar • Transformar*
- **Slogan:** *Cuidado com presença. Bem-estar onde você está.*
- **Paleta de Cores:** Bronze Nobre (`#633e24`), Ouro Champagne (`#b88a57`), Bege Aveludado (`#f7efe7`), Linho Off-White (`#fdfaf6`) e Café Profundo (`#2a1d15`).
- **Logo:** `https://i.postimg.cc/T1h7Q3wC/beatrizlogo.png`
- **WhatsApp:** `(11) 99999-9999`
- **Instagram:** `@R.R.estetica&massoterapia`

---

## 💆‍♀️ Procedimentos Inclusos (Sem Exibição de Preços)
1. **Higienização + Hidratação Facial** (45 min)
2. **Limpeza de Pele** (60-75 min)
3. **Drenagem Linfática** (50-60 min)
4. **Massagem Relaxante Terapêutica** (60 min)
5. **Massagem Relaxante Desportiva** (60 min)
6. **Massagem Relaxante** (60 min)
7. **Quick Massage** (15-30 min)
8. **Pedras Quentes** (75 min)
9. **Massagem com Bambu** (60 min)

---

## 📍 Região Atendida (Zona Sul de SP)
- Moema, Brooklin, Campo Belo, Vila Mariana, Saúde, Morumbi, Indianópolis, Jabaquara, Campo Limpo e imediações.

---

## 🛠️ Tecnologias
- **HTML5 Semântico:** SEO otimizado, Open Graph para compartilhamento e acessibilidade.
- **CSS3 Moderno:** Variáveis customizadas, Flexbox, Grid, animações suaves e design 100% responsivo para mobile, tablet e desktop.
- **JavaScript ES6+:** SPA interativo para agendamento, grade dinâmica de horários, cálculo e bloqueio de intervalos de agenda em tempo real.
- **Integração Google Apps Script & Sheets:** Envio automático de leads e verificação de horários em tempo real.
- **WhatsApp API:** Redirecionamento automático com mensagem formatada de confirmação.

---

## 📅 Como Configurar a Planilha da Beatriz (Google Sheets)

### 1. Criar a Planilha com as Colunas
Crie uma planilha no Google Sheets com os seguintes cabeçalhos na primeira linha:
> **A:** `ID` | **B:** `Data` | **C:** `Horário` | **D:** `Nome` | **E:** `WhatsApp` | **F:** `Bairro` | **G:** `Serviço` | **H:** `Status`

### 2. Adicionar o Script
1. Acesse **Extensões** > **Apps Script**.
2. Cole o código do `doGet` e `doPost` fornecido.
3. Clique em **Implantar** > **Nova Implantação**.
4. Selecione o tipo **App da Web**:
   - **Executar como:** *Eu*
   - **Quem tem acesso:** *Qualquer pessoa*
5. Copie a URL do Web App gerada e cole na constante `scriptURL` no arquivo `script.js`.
