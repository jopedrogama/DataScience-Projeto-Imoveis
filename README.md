# DataScience-Projeto-Imoveis

Escopo:
* Levantar sites que tenham anuncio de imóveis
* Verificar /robots.txt para saber se podemos fazer o scraping no site
* Criação do pipeline de ETL: Extração, Transformação e Load
    * Definir como será o scraping para cada site
    * Definir transformações necessárias
    * Alimentar nosso dataset com as informações para poder utilizar futuramente
    
    
## Sites


* https://www.zapimoveis.com.br/
* https://www.vivareal.com.br/
* https://www.lugarcerto.com.br/
* https://www.imovelweb.com.br/
* https://www.wimoveis.com.br/
* https://www.chavesnamao.com.br/
* https://www.quintoandar.com.br/

## Informações do Banco de Dados


* URL do anuncio - str
* MD5 para a URL - str
* Preço do imovel - float
* Preço IPTU - float
* Preço condominio (se tiver) - float
* m2 - total - int
* m2 - construido -int
* quartos -int
* banheiros -int
* vaga de garagem -int
* tipo (casa, condominio, apartamento) - str
* suite - int
* Corretora -boolean
* Endereco escrito -str
* Bairro -str
* Cidade -str
* Estado -str
* LatLog - PostGIS
* Data extracao