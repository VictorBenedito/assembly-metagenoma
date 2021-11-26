# Assembly Metagenoma

## Preparando o Ambiente
O requisito para executar este pipeline é ter instalado o *Gerenciador de Pacotes* **Conda**. Faça a instação da versão mais recente do [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) em sua máquina com antecedência.

Com o Conda instalado, podemos criar um novo ambiente com snakemake executando o seguinte comando:

```conda create -c conda-forge -c bioconda -n assembly-metagenoma snakemake -y```

Agora, precisamos ativar o ambiente criado. Para isso, executamos o comando:

```conda activate assembly-metagenoma```

Para copiar o conteúdo deste repositório, executamos o seguinte comando:

```git clone https://github.com/engbiopct/assembly-metagenoma.git```

Depois de clonar o repositório, é possível entrar no diretório recém-criado e modificar o arquivo de configuração com os parâmetros e amostras apropriados:

```cd assembly-hiseq```

