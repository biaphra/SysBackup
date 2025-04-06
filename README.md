SysBackup
Autor: Biaphra Araujo
E-mail: contato@biaphra.com.br
Linkedin: https://www.linkedin.com/in/695066353/

Um aplicativo de backup automatizado desenvolvido com Python e PySide6.

## Características

- Seleção personalizada de pastas para backup
- Agendamento automático de backups
- Opção de compactação em ZIP ou RAR
- Interface moderna e intuitiva
- Inicialização automática com o Windows
- Desligamento automático após backup
- Configurações salvas em JSON

## Requisitos

- Python 3.8 ou superior
- PySide6
- WinRAR (necessário para compactação RAR)

## Instalação

1. Clone ou baixe este repositório
2. Instale as dependências:
```bash
pip install -r requirements.txt
```

## Uso

Execute o aplicativo com:
```bash
python main.py
```

## Configuração

1. Adicione pastas para backup usando o botão "Adicionar"
2. Selecione a pasta de destino para os backups
3. Escolha o tipo de compressão (ZIP ou RAR)
4. Configure o agendamento se desejar
5. Ative/desative opções adicionais como necessário
6. Clique em "Salvar Configurações"

## Notas

- Para usar a compactação RAR, é necessário ter o WinRAR instalado no sistema
- As configurações são salvas em `%USERPROFILE%/sysbackup_config.json`
- O aplicativo pode ser configurado para iniciar automaticamente com o Windows
