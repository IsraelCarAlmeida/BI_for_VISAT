# BI_for_VISAT

## Link para o dashboard online 

## Para acessar os dados ou o arquivo físico do dashboard baixe a pasta BI_for_VISAT
### Para abrir o dashboard será necessário fazer a instalçao do power bi na sua máquina, tutorial recomendado (https://www.hashtagtreinamentos.com/como-instalar-o-power-bi)

## Para executar os códigos siga as orientações abaixo:
* Baixe o arquivo Pipeline_ACGR_SINAN.ipynb que está na pasta BI_for_VISAT e adicione no seu drive;
* Selecione a opção "abrir como Google Colaboratory";
* Acessando o arquivo execute a primeira etapa "Instação da biblioteca pysus". Se der timeout espere por algumas horas e tente executar novamente;
* Antes de executar a etapa "Extração e transformações iniciais" é preciso fazer o upload dos arquivos "municipios_BR.csv" e "CID-10_Categorias.csv", isso pode ser feito manualmente ou puxando do drive utilizando python;
* Execute a etapa "Instalação do pyspark";
* Execute a etapa "Consolidação dos arquivos";
* Execute a etapa "Transformações finais";
* Após a finalização do fluxo, baixe o arquivo que está na gold e renomeie para "ACGR_2007_2023_ouro.parquet". Clicando no símbolo de uma pasta do lado esquerdo vão ser exibidas as pastas do projeto, clicando nos três pontinhos ao lado de cada arquivo irá ser exibida a opção de baixá-lo. Se o código foi alterado renomeie para algo que faça mais sentido, mas ele terá que ser importado novamente e talvez o dashboard precise ser alterado;
* Substituia o arquivo na pasta BI_for_VISAT;
* Abre o dashboard e clique em atualizar dados. Se o arquivo não foi nomeado corretamente ou sofreu mudanças estruturais, provavelmente será exibido um erro, para mais detalhes olha na documentação oficial da microsoft.
