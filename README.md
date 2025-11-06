# AED 2025 — Trabalho 1: Imagens com Cor Indexada (Pseudocor)

## Divisão de Tarefas

- `Image ImageCopy(img)` - Miguel
- `int ImageIsEqual(img1, img2)` - Margarida
- `Image ImageRotate90CW(img)` - Margarida
- `Image ImageRotate180CW(img)` - Miguel
- `int ImageRegionFillingRecursive(img, u, v, color)` - Margarida
- `int ImageRegionFillingWithQUEUE(img, u, v, color)` - Miguel
- `int ImageRegionFillingWithSTACK(img, u, v, color)` - Margarida
- `int ImageSegmentation(img, fillFunct)` - Miguel

---

## Análise Experimental e Formal

Função alvo: `int ImageIsEqual(img1, img2)`

- Realizar testes com imagens de diferentes tamanhos e conteúdos
- Medir número de comparações e tempo de execução
- Analisar complexidade teórica
- Comparar resultados experimentais com a análise formal

---

## Relatório

O relatório deve incluir:

- Descrição de cada função (cada membro escreve a sua)
- Justificação das decisões de implementação
- Resultados dos testes realizados
- Comparação entre estratégias de preenchimento de regiões (recursiva, com fila, com pilha)

---

## Testes Unitários

Sugestão: criar um ficheiro dedicado para testes unitários que verifique o funcionamento de todas as funções implementadas.

Exemplo:
```c
int main() {
    test_ImageCopy();
    test_ImageIsEqual();
    test_ImageRotate90CW();
    test_ImageRotate180CW();
    test_ImageRegionFillingRecursive();
    test_ImageRegionFillingWithQUEUE();
    test_ImageRegionFillingWithSTACK();
    test_ImageSegmentation();
    return 0;
}
