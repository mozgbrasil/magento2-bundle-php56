![valid XHTML][checkmark]
[checkmark]: https://raw.githubusercontent.com/mozgbrasil/mozgbrasil.github.io/master/assets/images/logos/Red_star_32_32.png "MOZG"
[packagist]: https://packagist.org/packages/mozgbrasil/
[requirements]: http://mozgbrasil.github.io/requirements/
[integracao-correios]: https://github.com/mozgbrasil/magento2-correios-php56#mozgcorreios
[integracao-jamef]: https://github.com/mozgbrasil/magento2-jamef-php56#mozgjamef
[integracao-jadlog]: https://github.com/mozgbrasil/magento2-jadlog-php56#mozgjadlog
[getcomposer]: https://getcomposer.org/
[uninstall-mods]: http://devdocs.magento.com/guides/v2.1/install-gde/install/cli/install-cli-uninstall-mods.html

# Mozg\Bundle

## Sinopse

Este é um meta pacote que instala todos os módulos da Mozg via [packagist.org][packagist] no Magento2

## Motivação

Atender o mercado de módulos para Magento oferecendo melhorias e um excelente suporte

## Característica técnica

Um meta-pacote é um pequeno pacote praticamente sem conteúdo algum.

A principal função deste tipo de pacote são suas dependências de outros pacotes, pois eles servem como um guia para pacotes específicos serem instalados, com suas devidas configurações. 

## Instalação - Atualização - Desinstalação

Este módulo destina-se a ser instalado usando o [Composer][getcomposer]

Antes de executar os processos, [clique aqui][requirements] e leia os pré-requisitos e sugestões

--

### Para instalar o módulo execute o comando a seguir no terminal do seu servidor

	composer require mozgbrasil/magento2-bundle-php56 && php bin/magento setup:upgrade

--

### Para atualizar o módulo execute o comando a seguir no terminal do seu servidor

	composer update && php bin/magento setup:upgrade

--

### Para [desinstalar][uninstall-mods] o módulo execute o comando a seguir no terminal do seu servidor

	composer remove mozgbrasil/magento2-bundle-php56 && composer clear-cache && composer update && php bin/magento setup:upgrade

## Perguntas mais frequentes "FAQ"

### Serviços de exibição de performance

http://www.webpagetest.org/

https://gtmetrix.com/

## Contribuintes

Equipe Mozg

## Badges

[![Join the chat at https://gitter.im/mozgbrasil](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/mozgbrasil/)
[![Latest Stable Version](https://poser.pugx.org/mozgbrasil/magento2-bundle-php56/v/stable)](https://packagist.org/packages/mozgbrasil/magento2-bundle-php56)
[![Total Downloads](https://poser.pugx.org/mozgbrasil/magento2-bundle-php56/downloads)](https://packagist.org/packages/mozgbrasil/magento2-bundle-php56)
[![Latest Unstable Version](https://poser.pugx.org/mozgbrasil/magento2-bundle-php56/v/unstable)](https://packagist.org/packages/mozgbrasil/magento2-bundle-php56)
[![License](https://poser.pugx.org/mozgbrasil/magento2-bundle-php56/license)](https://packagist.org/packages/mozgbrasil/magento2-bundle-php56)
[![Monthly Downloads](https://poser.pugx.org/mozgbrasil/magento2-bundle-php56/d/monthly)](https://packagist.org/packages/mozgbrasil/magento2-bundle-php56)
[![Daily Downloads](https://poser.pugx.org/mozgbrasil/magento2-bundle-php56/d/daily)](https://packagist.org/packages/mozgbrasil/magento2-bundle-php56)

:cat2:
