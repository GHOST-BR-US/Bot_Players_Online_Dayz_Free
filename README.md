# 🎮 Players Online DayZ

Bot para exibir status do servidor DayZ no Discord (players, mapa, slots e horário).

---

## 📞 Suporte

* 🌐 Site: https://gtbrsistemas.com
* 💬 Discord: https://discord.gg/YTjYy8AXf9

---

## ⚙️ Configuração

### 🔹 PASSO 01 — TOKEN DO BOT

`token` → Token do bot Discord

Para obter seu token:

1. Acesse: https://discord.com/developers/applications
2. Crie ou selecione uma aplicação
3. Vá em **Bot**
4. Clique em **Redefinir Token**
5. Copie o token

Para adicionar o bot ao servidor:

```
https://discord.com/oauth2/authorize?client_id=ID_DO_BOT_AQUI&scope=bot&permissions=8
```

---

### 🔹 PASSO 02 — CANAL DE STATUS

`id_canal_msg_status` → Canal onde o bot envia o embed

---

### 🔹 PASSO 03 — CATEGORIA

`id_categoria_do_canal_msg_status` → Categoria onde o canal de voz será criado

---

### 🔹 PASSO 04 — TEMPO DE ATUALIZAÇÃO

`tempo_de_atualizacao` → Tempo em segundos
Recomendado: **60**

---

### 🔹 PASSO 05 — NOME DO SERVIDOR

`nome_do_servidor` → Nome exibido no bot

---

### 🔹 PASSO 06 — IP DO SERVIDOR

`ip_servidor` → IP do servidor
Exemplo: `00.00.00.000`

---

### 🔹 PASSO 07 — PORTA QUERY

`servidor_query_port` → Porta de consulta
Exemplo: `2303`

---

### 🔹 PASSO 08 — OFFLINE

`msg_servidor_offline` → Mensagem quando offline
Exemplo: `🔴 Offline`

---

### 🔹 PASSO 09 — EMOJIS (Opcional)

```json
"emojis": {
  "players": {
    "servidor_vazio": "⚫",
    "poucos_players": "🟢",
    "pela_metade": "🟡",
    "quase_cheio": "🟠",
    "servidor_lotado": "🔴"
  },
  "tempo": {
    "nascer_do_sol": "🌅",
    "dia": "☀️",
    "entardecer": "🌇",
    "noite": "🌙"
  }
}
```

💡 Você pode alterar os emojis livremente.
