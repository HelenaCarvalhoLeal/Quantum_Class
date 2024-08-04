# Instalando o Qiskit

## Passo 1: Instalação do Miniconda
Primeiramente, instale o Miniconda seguindo o [link para o download](https://docs.anaconda.com/free/miniconda/index.html). Selecione sua plataforma, baixe e instale conforme as instruções.

## Passo 2: Configuração do Ambiente
Uma vez instalado, abra o Anaconda Prompt (Miniconda3). No Windows, você pode fazer isso pressionando a tecla Windows, digitando “Anaconda” e depois pressionando sobre Anaconda Prompt (Miniconda3). Um terminal será aberto mostrando:
```
(base) C:\User\Nome>
```

## Passo 3: Criar um Environment
Agora, crie um ambiente virtual onde o Qiskit será instalado. Digite o comando:
```
conda create --name qiskit
```
Você pode substituir `qiskit` por outro nome de sua escolha para o environment.

## Passo 4: Ativar o Environment
Ative o ambiente criado com o comando:
```
conda activate qiskit
```
Se você usou outro nome para o environment, troque `qiskit` pelo nome que você escolheu. Feito isso, seu prompt deverá se parecer com isso:
```
(qiskit) C:\User\Nome>
```
Isso indica que você está no ambiente qiskit. Sempre que for trabalhar com o Qiskit, repita este passo para ativar o ambiente.

## Passo 5: Instalação de Pacotes
Agora que estamos no ambiente qiskit, precisamos instalar os pacotes que serão necessários. Primeiro, instale o pip dentro do ambiente:
```
conda install pip
```
Em seguida, instale o Qiskit:
```
pip install qiskit
```
Instale também a biblioteca de visualização de dados matplotlib:
```
pip install matplotlib
```
E a ferramenta de conexão com o ambiente de execução da IBM:
```
pip install qiskit_ibm_runtime
```
Para codificação em LaTeX:
```
pip install pylatexenc
```
Por fim, instale o Jupyter Lab, onde você escreverá seus códigos:
```
pip install jupyterlab
```

## Passo 6: Executar Jupyter Lab
Digite o comando abaixo para iniciar o Jupyter Lab:
```
jupyter-lab
```
Na primeira execução, selecione um navegador para usar como interface.

## Passo 7: Abrir um Notebook e testar a Instalação
No Jupyter Lab, na seção Notebook, dê um duplo clique em “Python 3 (ipykernel)”. Para testar se o Qiskit foi instalado corretamente, digite:
```python
import qiskit
```
Pressione SHIFT + ENTER para executar. Isso irá carregar o Qiskit. Para verificar a versão do Qiskit, digite:
```python
qiskit.__version__
```
Pressione novamente SHIFT + ENTER para exibir a versão instalada. Esses passos concluem a instalação do Qiskit.

## Passo 8: Utilizar o Qiskit depois da primeira vez
Abra o Anaconda Prompt (Miniconda3). Um terminal será aberto mostrando:
```
(base) C:\User\Nome>
```
Ative novamente o ambiente criado com o comando:
```
conda activate qiskit
```
Inicie o Jupyter Lab:
```
jupyter-lab
```

Obs.: Créditos ao professor Felipe Fernandes Fanchini pelo tutorial descrito acima e ao canal Qiskit no YouTube.
