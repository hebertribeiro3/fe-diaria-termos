git clone https://github.com/hebertribeiro3/fe-diaria-termos.git
cd fe-diaria-termos
echo "# Política de Privacidade - Fé Diária

**Última atualização: Maio de 2026**

Esta Política de Privacidade descreve como o aplicativo **Fé Diária**, desenvolvido por Hebert Ribeiro, lida com as informações dos usuários. O nosso compromisso é garantir a sua privacidade e proporcionar uma experiência segura e focada na sua vida de oração e meditação.

## 1. Coleta e Uso de Informações Pessoais
O aplicativo **Fé Diária** é projetado para respeitar a sua privacidade de forma absoluta. **Nós não coletamos, não armazenamos e não compartilhamos** nenhum tipo de informação pessoal identificável. O aplicativo não exige criação de conta.

## 2. Armazenamento Local de Dados
O aplicativo salva preferências (tamanho da fonte, horários) diretamente no seu dispositivo. Esses dados não são transmitidos para servidores externos.

## 3. Serviços de Terceiros e APIs
O aplicativo consulta APIs públicas de Liturgia e Bíblia. Além disso, envia os textos do Evangelho para a API do Google Gemini para gerar a homilia diária. **Nenhum dado pessoal do usuário é enviado nessas requisições.**

## 4. Notificações
O aplicativo utiliza notificações locais agendadas pelo próprio sistema do aparelho.

## 5. Contato
Dúvidas ou sugestões: **hebertribeiro3@gmail.com**" > PRIVACY_POLICY.md

git add PRIVACY_POLICY.md
git commit -m "Adiciona Política de Privacidade"
git push origin main
