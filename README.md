# Study of Python

## Validar a versão do Python
```bash
python --version
python -v
```

## Exibe a política de execução atual
```powershell
Get-ExecutionPolicy
```

## Alterar a política de execução (se necessário)
```powershell
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```

## Criar um ambiente virtual Python
```bash
python -m venv venv
```

## Ativar o ambiente virtual
### Windows (cmd)
```cmd
venv\Scripts\activate
```

### Windows (PowerShell)
```powershell
.\venv\Scripts\Activate
```

### Linux/Mac
```bash
source venv/bin/activate
```

## Desativar o ambiente virtual
```bash
deactivate
```

## Instalar pacotes no ambiente virtual
```bash
pip install <nome-do-pacote>
```

## Gerar um arquivo requirements.txt
```bash
pip freeze > requirements.txt
```

## Instalar pacotes a partir de requirements.txt
```bash
pip install -r requirements.txt
```

### Explicação dos comandos:
- **python**: chama o interpretador Python instalado no sistema.
- **-m venv**: diz ao Python para executar o módulo `venv`, que é usado para criar ambientes virtuais.
- **venv**: é o nome da pasta onde o ambiente virtual será criado (você pode escolher outro nome, como `.venv`, `env`, etc).
- **pip**: gerenciador de pacotes do Python, usado para instalar, atualizar e remover pacotes.
