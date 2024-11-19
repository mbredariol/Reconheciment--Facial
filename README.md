
# Image Text Recognition Project

## Objetivo
Este projeto demonstra a extração de texto de imagens usando ferramentas de reconhecimento, como o Vision Studio.

## Estrutura do Repositório
- `inputs/`: Contém as imagens originais usadas no projeto.
- `outputs/`: Contém os textos extraídos das imagens.
- `README.md`: Explica o processo, desafios e aprendizados.

## Processo
1. **Ferramenta Utilizada**: Vision Studio
   - Funcionalidade: "Read text in Vision Studio".
2. **Etapas**:
   - Imagens foram carregadas na ferramenta a partir da pasta `inputs/`.
   - O texto detectado foi exportado para arquivos `.txt` na pasta `outputs/`.

## Insights
- Algumas imagens apresentaram dificuldades na detecção de texto devido à qualidade da imagem.
- A precisão foi maior em textos com contraste adequado e fundo claro.

## Exemplos de Resultados
### Imagem Original (`inputs/receipt_example.png`):
Recibo simples de um supermercado.

### Texto Detectado (`outputs/receipt_text.txt`):
```
Supermercado Exemplo
Arroz - R$ 10,00
Feijão - R$ 7,50
Macarrão - R$ 5,00
Data: 19/11/2024
```

### Imagem Original (`inputs/event_flyer_example.png`):
Cartaz colorido de um evento.

### Texto Detectado (`outputs/event_text.txt`):
```
Show de Talentos
Sábado, 25 de Novembro de 2024
Horário: 19:00
Local: Teatro Central
Contato: Telefone: (11) 98765-4321
```
