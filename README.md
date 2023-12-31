### Projeto

Senhas são um dos pontos de vulnerabilidade mais explorados por criminosos cibernéticos. O motivo disso é simples, eles sabem que muitos usuários são descuidados e criam senhas fáceis de quebrar.

Pensando nisso a empresa XPTO decidiu desenvolver um verificador de força de senha que deverá ser usado toda vez que um usuário precisar alterar sua senha.

O verificador de força de senha se baseia nas seguintes regras:
- Se a senha tiver mais de 1 caractere - 1 ponto;
- Se a senha tiver mais de 6 caracteres - 2 pontos;
- Se a senha tiver 10 ou mais caracteres - 3 pontos;
- Se a senha tiver 12 ou mais caracteres - 4 pontos;
- Se a senha tiver 14 ou mais caracteres - 5 pontos;
- Se a senha contiver pelo menos um número - +1 ponto;
- Se a senha contiver pelo menos uma letra maiúscula - +1 ponto;
- Se a senha contiver pelo menos um caractere minusculo - +1 ponto;
- Se a senha contiver pelo menos um caractere especial (não alfanumérico) - +2 pontos;

Total de pontos possíveis: 10.

- A senha será considerada "Forte" se somar 9 ou mais pontos;
- A senha será considerada "Moderada" se somar mais de 5 e menos de 9 pontos;
- A senha será considerada "Fraca" se somar 5 ou menos pontos.

![Força de Senha](src/IMG/d18932db-c62f-499d-9277-e171a21209e5.gif)
