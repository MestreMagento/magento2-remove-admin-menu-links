# Magento 2 - Remover os Links do Menu do Administrador

Esse modulo permite remover links indesejados do menu principal do Magento.

Toda semana novas aulas, inscreva-se em nosso canal do Youtube!
<a href="https://www.youtube.com/mestremagento">https://www.youtube.com/mestremagento</a>

## Primeiros Passos

Faça o <a href="https://github.com/MestreMagento/magento2-remove-admin-menu-links/archive/master.zip">download do repositório</a> e coloque dentro da pasta /app/code/<b>MestreMagento</b>/<b>OrganizeMenuAdmin/</b>.

### Ambiente/Versão

Este módulo atende as verões:
Magento 2.0.x / 2.1.x / 2.2.x

### Instalação

Faça o download do repositório <a href="https://github.com/MestreMagento/magento2-remove-admin-menu-links/archive/master.zip">aqui</a>.

Extraia os arquivos na pasta que indicamos abaixo:
```
/app/code/MestreMagento/OrganizeMenuAdmin/
```

Coloque sua loja em modo desenvolvimento:
```
php bin/magento deploy:mode:set developer
```

Ative o modulo:
```
php bin/magento module:enable -c MestreMagento_OrganizeMenuAdmin
```

Registre o modulo:
```
php bin/magento setup:upgrade
```

Publique os arquivos estáticos:
```
php bin/magento setup:static-content:deploy
```
