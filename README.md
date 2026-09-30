# PainelTeste — Dashboard Educacional FAETEC

Dashboard de indicadores de vagas, inscrições e matrículas da FAETEC (2018–2026), com login embutido no próprio arquivo HTML.

## Conteúdo
- `index.html`: o dashboard completo, autocontido. Os dados ficam criptografados (AES-256-GCM) dentro do arquivo e só são abertos após o login.

## Como usar
Abra `index.html` em um navegador (ou publique com GitHub Pages). Peça usuário e senha a quem administra.

## Administração de usuários
- **Dentro do Claude** (na página publicada em claude.ai): quem for administrador vê o link "Administração" e pode criar, desativar, redefinir senha e excluir usuários. Essas mudanças ficam salvas no banco de dados do artefato do Claude.
- **Nesta cópia do GitHub:** o login funciona de forma independente, com uma cópia (snapshot) dos usuários existentes no momento do envio. A tela de Administração fica indisponível aqui, porque não há um servidor para gravar alterações.
- **Para atualizar os usuários desta cópia:** peça para o Claude gerar um novo `index.html` com o snapshot mais recente dos usuários e reenviar a este repositório.

## Dados
Fonte: planilha "DADOS" (FAETEC). Períodos de 2018/1 a 2026/2, atualizada em 29/09/2026.

## Aviso
Repositório privado. Os dados dentro do arquivo estão criptografados; a senha de cada usuário é o único jeito de abri-los. Trocar a senha de um usuário (feito dentro do Claude) não afeta esta cópia até que ela seja reenviada.
