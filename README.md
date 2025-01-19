# BI_for_VISAT

## Link para o dashboard online
Em desenvolvimento

## Para acessar os dados ou o arquivo físico do dashboard baixe a pasta BI_for_VISAT
Para abrir o dashboard será necessário fazer a instalaçao do power bi na sua máquina, tutorial recomendado: https://www.hashtagtreinamentos.com/como-instalar-o-power-bi

## Diagrama do pipeline
Fluxo de extração, tratamento, transformação e disponibilização dos dados:
https://drive.google.com/file/d/1NqhP4FXB5nWeu-8aKE350BhMjD2IYgG7/view?usp=sharing

## Para executar os códigos e atualizar os dados siga as orientações abaixo:
* Baixe a pasta BI_for_VISAT e adicione o arquivo Pipeline_ACGR_SINAN.ipynb no seu drive;
* Selecione a opção "abrir com Google Colaboratory";
* Acessando o arquivo execute a primeira etapa "Instação da biblioteca pysus";
* No Google Colaboratory clique no símbolo da pasta a esquerda da tela;
* Antes de executar a etapa "Extração e transformações iniciais" é preciso fazer o upload dos arquivos "municipios_BR.csv" e "CID-10_Categorias.csv";
* Execute a etapa "Instalação do pyspark";
* Execute a etapa "Consolidação dos arquivos";
* Execute a etapa "Transformações finais";
* Após a finalização do fluxo, baixe o arquivo que está na gold e renomeie para "ACGR_2007_2023_ouro.parquet";
* Substitua o arquivo na pasta BI_for_VISAT da sua máquina;
* Instale o power bi (se necessário);
* Abre o dashboard e clique em atualizar dados.
