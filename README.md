# 🥼 Nutri

Desenvolvido durante o Workshop Pythonando PSW4. 

Projeto destinado a nutricionistas para fazerem o gerenciamento de pacientes. 

#

### 📑 Versões das tecnologias usadas:

<table>
  <tr>
    <td>Python</td>
    <td>Django</td>    
    <td>SQLite</td>
    <td>Bootstrap</td>
    <td>CSS</td>
    <td>HTML</td>
  </tr>
  <tr>
    <td>3.*</td>
    <td>4.0.6</td>
    <td>3</td>
    <td>5</td>
    <td>3</td>
    <td>5</td>
  </tr>
</table>

#

### 🔨 Funcionalidades:

- Realizar o Login/Logout
- Criar/Registrar uma conta
- Ativação de conta via token enviado por email
- Cadastrar clientes
- Visualizar clientes
- Adicionar refeições
- Adicionar opções para as refeições
- Inserir dados dos clientes/pacientes (peso, gordura corporal, colesterol, etc...)
- Inserir fotos de refeições
- Visualizar gráficos do histórico de peso dos pacientes

#

### 📷 Imagens:
![pictures](https://user-images.githubusercontent.com/78339857/184227795-43ebd641-cdd8-4fb3-a98b-610921677801.jpg)
![pictures1](https://user-images.githubusercontent.com/78339857/184227853-64a1504e-9407-4ab1-af7a-a3c01a52a252.jpg)

#

### 🛠️ Instalando o projeto:

- Clone o repositório:
```
$ git clone https://github.com/RakelMacedo/nutri.git
$ cd nutri/
```

- Crie seu ambiente virtual:
```
$ python3 -m venv .venv
```

- E ative seu ambiente virtual:
```
$ source .venv/bin/activate
```

- Instale as depencências:
```
$ pip install -r requirements.txt
```

- Crie a estrutura no banco de dados:
``` 
$ python3 manage.py migrate
```  

- Inicie o servidor de desenvolvimento:
```
$ python3 manage.py runserver
```

### ✅ Prontinho! Com o servidor rodando, basta você visitar os endpoints do projeto com o seu navegador! =)
