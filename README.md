**Como testar o projeto**

1. Abrir o repositório pelo PyCharm;

2. Criar um ambiente virtual "venv" para executar o projeto, através do comando;
   ```
     python -m venv venv
     venv\Scripts\activate
   ```

3. Instalar as bibliotecas Flask e FDB;
   ```
     pip install flask
     pip install fdb
   ```

4. Alterar o endereço do banco de dados no arquivo "main.py";

5. Inicializar o projeto.


**Detalhes importantes**
- É necessário que o Firebird SQL verão 4.0 esteja instalado no computador;
- Lembre-se de configurar corretamente o interpretador python no PyCharm.
