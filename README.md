# dicas-html

1.  [datalist](#datalist)
2.  [time](#time)

## **Datalist**

O elemento <datalist> do HTML permite implementar um preenchimento automático utilizando somente tags nativas.

```html
<label for="movie-choice">Escolha um filme:</label>
<input list="movies" id="movie-choice" />

<datalist id="movies">
  <option value="Harry Potter e a Pedra Filosofal"></option>
  <option value="Harry Potter e a Câmara Secreta"></option>
  <option value="Harry Potter e o Prisioneiro de Azakaban"></option>
  <option value="Harry Potter e o Cálice de Fogo"></option>
  <option value="Harry Potter e a Ordem da Fênix"></option>
  <option value="Harry Potter e o Enigma do Príncipe"></option>
  <option value="Harry Potter e as Relíquias da Morte: Parte 1"></option>
  <option value="Harry Potter e as Relíquias da Morte: Parte 2"></option>
</datalist>
```

## **Time**

O elemento <time> do HTML representa um período específico no tempo. Para traduzir as datas em um formato machine-readable, podemos incluir o atributo "datetime". Dessa forma, permitimos melhores resultados em mecanismos de pesquisa ou recursos personalizados, como lembretes.

```html
<p>O horário de funcionamento é das <time>08:00</time> às <time>17:00</time></p>
<p>Não abriremos no <time datetime="2023-12-25">natal</time></p>
```

**[⬆ Voltar para o início](#dicas-html)**
