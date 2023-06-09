Projeto prático sobre ->
localStorage:
localStorage, é um recurso para salvar dados no navegador, que persiste até mesmo após o recarregamento da página ou ao fechar a aba;
Os dados armazenados no localStorage não expiram e permanecerão enquanto o usuário não limpar o cache do navegador.
Tem a capacidade máxima de 10 MegaByte (mb) como iremos salvar apenas textos, é bastante coisa;
Esses dados são salvos no próprio computador do usuário, ou seja, precisamos ter cuidado com o que colocamos lá, pois o usuário pode acessar os dados que nele estão.
Eles não possuem tempo de expiração, mas podem ser removidos;
Os dados ficam na aba Application do Dev Tools (Console do Navegador);
Exemplo prático:
Quando precisamos guardar um dado que o usuário sempre irá precisar quando acessar o nosso site, exemplo o theme que ele escolher se for dark ou light, ou qualquer outro tipo de configuração que o usuário fizer em nosso site.

Explicação do Projeto:
Esse projeto consiste em o usuário informar seu nome e logar no “sistema”, e quando o mesmo fechar a aba do navegador ou recarregar, ele sempre irá ter o acesso até que ele clique em “sair”, dessa maneira o usuário dele é “esquecido” pelo sistema, logo irá precisar informar seu nome novamente.
