# hub-monitor

Monitor externo do Hub de Dados do Sienge (RDO): a cada 15 minutos o GitHub Actions faz um GET no endpoint
público de saúde do hub. Se o servidor, o túnel ou o serviço estiverem fora, o workflow falha e o GitHub avisa por
e-mail. O endpoint não expõe dado de negócio (só o estado do serviço e o nível do monitor interno).

Repositório público só com o workflow: em repositório público o Actions não consome a cota da conta.
