# Assembly Metagenoma

O único requisito para executar este pipeline é o Anaconda 3 . Por favor, instale a versão mais recente do [Anaconda 3](https://www.anaconda.com/products/individual) em sua máquina com antecedência.

Com o Anaconda instalado, podemos criar um novo ambiente com snakemake executando o seguinte comando:

```conda create -c conda-forge -c bioconda -n assembly-hiseq snakemake -y```
Por alguma razão, o Snakemake não pode ativar ambientes conda automaticamente, portanto, você precisa copiar o binário de ativação de sua pasta principal conda para o ambiente que você criou para usar este pipeline. Por exemplo:v
