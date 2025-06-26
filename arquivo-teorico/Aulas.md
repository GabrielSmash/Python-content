# Indice
- [Introdução](#curso-python-completo)
- [Instalação do Pyhton](#instalação-do-python-e-vscode)

---
# Curso Python Completo
> Repositorio destinado ao meu foco atual, Pyhton.  
> O curso ira percorrer do nivel Iniciante até Avançado.  
> Algumas tencnologias exploradas:
> - PySide6
> - Django
> - Selenium
> - Regexp
> - TDD
> - Testes
> - POO
> - Design Pattern GoF
> - Algoritmos

## Instalação do Python e VSCode
[Download Python](https://www.python.org/downloads/)  
[Download VSCode](https://code.visualstudio.com/download)  
> Adicionar o Python ao PATH  

**Configuração PowerShell**
- Executar como Administrador
    - Digite: `Get-ExecutionPolicy`
        - > O resultado pode ser *Restricted*
        - Digite: `Set-ExecutionPolicy Unrestricted -Force`
            - > O resultado deve ser *Unrestricted*
    - Com *Unrestricted* voce podera criar livremente maquinas virtuais
    - Criando o ambiente virtual:
        - Digite: `python -m venv venv`
            - > Ele deve criar o ambiente virtual
            - Digite: `.\venv\Scripts\activate`
                - > Ele entra no ambiente virtual
                - > Qualquer solicitação de autorização deve ser permitida  

**Configuração VSCode**
- Clique em Manage
    - Clique no icone `Open Settings(JSON)`
    - Adicione as configurações:
        - `"editor.fontSize": 14`
            - > Edita o tamanho da fonte
        - `"explorer.compactFolders": false`
            - > Desativa as pastas compactas
