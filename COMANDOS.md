# Comandos EcoPower

## SITE ESSENCIAL
Comando: "Fazer site essencial: [cole aqui os dados do email]"

## SITE PREMIUM  
Comando: "Fazer site premium: [cole aqui os dados do email]"

---

## INSTRUÇÕES PARA O CLAUDE CODE

Quando receber o comando "Fazer site essencial" ou "Fazer site premium":

1. Ler os dados colados pelo usuário
2. Clonar a branch template-base do repositório:
   git clone -b template-base https://github.com/timedepresidentes-blip/ecopower-araraquara.git ecopower-[cidade]
3. Substituir no index.html todos os dados de Araraquara pelos dados do franqueado:
   - Cidade, estado, email, WhatsApp, endereço, bairro, horário
4. Fazer deploy no Netlify
5. Retornar a URL do site pronto
