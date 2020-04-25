1) Criando o ambiente  
pwd (Aqui vai aparecer o caminho completo do diretorio)  
python3 -m venv < caminho completo do diretorio >/venv  
  
2) Atualizando o ambiente com as bibliotecas do projeto  
source ./venv/Scripts/activate  
pip install -r requirements.txt  
  
3) Inserindo nova biblioteca  
source ./venv/Scripts/activate  
pip install <biblioteca>  
pip freeze > requirements.txt  
  
4) Ativando ambiente  
source ./venv/Scripts/activate  
  
5) Desativando ambiente  
deactivate  
  
Sequencia dentro do Gitbash  
pwd (Aqui vai aparecer o caminho completo do diretorio)  
python3 -m venv < caminho completo do diretorio >/venv  
source ./venv/Scripts/activate  
pip install pytest  
pip freeze > requirements.txt  
head requirements.txt  

