# crypto-uniq-code

Este script cria códigos únicos combinando:

1. Um número sequencial 1,2,3 ... convertido para **Base36**  
2. Um **HMAC** com chave secreta para garantir segurança e imprevisibilidade

O resultado é um código curto de 10 chars, seguro e sem risco de repetição.

<!-- ---

## Como usar

### 1. Crie um arquivo `.env`
```
SECRET_KEY=
```

### 2. Instale as dependências
```
pip install -r requirements.txt
```

### 3. Execute o script
```
python main.py
```

O script irá gerar 50 códigos de exemplo, exibindo:
- Número sequencial  
- Versão em Base36  
- Primeiros caracteres do HMAC  

--- -->

<!-- ## Observação
O valor `SEQUENTIAL_NUMBER` deve ser buscado do banco de dados na aplicação real. Aqui ele está fixo apenas para demonstração. -->
