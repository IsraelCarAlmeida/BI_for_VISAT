# BI_for_VISAT

## Link para o dashboard online
[https://app.powerbi.com/view?r=eyJrIjoiYTc5ZGY0NmEtMjUyMi00MzhlLWI3MDAtYjNjZWY3Y2IzZWYwIiwidCI6IjZjOTNlZTgyLWM2NTUtNGVkMi1hNDAyLTllMjRmOGU5ZTcxOCJ9](https://abrir.link/ILLTT)

## Para acessar os arquivos do projeto:
* Criar a pasta BI_for_VISAT no disco local C da máquina;
* Acessar e baixar o arquivo do dashboard: https://drive.google.com/file/d/1JA2tSwVa7LKQnvasuLVBi1hLYzXsPgnj/view?usp=sharing
* Acessar e baixar o arquivo com os dados das notificações: https://drive.google.com/file/d/1ois322Or5O_B-eGl6uiEFZJw-dZF1rRj/view?usp=sharing
* Adicionar os dois arquivos na pasta BI_for_VISAT;
* Para abrir o dashboard será necessário fazer a instalaçao do power bi na sua máquina, tutorial recomendado: https://www.hashtagtreinamentos.com/como-instalar-o-power-bi
* Abrir o dashboard e clicar em atualizar os dados.

## Diagrama do pipeline
Fluxo de extração, tratamento, transformação e disponibilização dos dados:
https://drive.google.com/file/d/1NqhP4FXB5nWeu-8aKE350BhMjD2IYgG7/view?usp=sharing

## Para executar os códigos e atualizar os dados:
* Adicionar o arquivo Pipeline_ACGR_SINAN.ipynb no seu drive;
* Selecionar a opção "abrir com Google Colaboratory";
* Acessar o arquivo e executar a primeira etapa "Instalação da biblioteca pysus";
* No Google Colaboratory clique no símbolo da pasta a esquerda da tela;
* Antes de executar a etapa "Extração e transformações iniciais" é preciso fazer o upload dos arquivos "municipios_BR.csv" e "CID-10_Categorias.csv";
* Executar a etapa "Extração e transformações iniciais";
* Executar a etapa "Instalação do pyspark";
* Executar a etapa "Consolidação dos arquivos";
* Executar a etapa "Transformações finais";
* Após a finalização do fluxo, baixe o arquivo que está na gold e renomeie para "ACGR_2007_2023_ouro.parquet";
* Substitua o arquivo na pasta BI_for_VISAT no disco local C da sua máquina;
* Instale o power bi (se necessário);
* Abrir o dashboard e clicar em atualizar os dados.
