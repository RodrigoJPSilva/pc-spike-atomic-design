**Atomic Design** é uma metodologia de criação de interfaces desenvolvida por **Brad Frost**, que organiza os componentes de um design de forma hierárquica e reutilizável, inspirada na química (átomos, moléculas, etc.). O objetivo é tornar o desenvolvimento de interfaces **mais modular, consistente e escalável**.

### Os 5 níveis do Atomic Design:

1. **Átomos (Atoms)**
    
    São os **elementos mais básicos da interface**, como:
    
    - Botões simples
    - Ícones
    - Inputs
    - Cores
    - Tipografia
    Eles não funcionam sozinhos como interface, mas são os blocos fundamentais.
2. **Moléculas (Molecules)**
    
    São **combinações de átomos** que funcionam juntos como uma unidade funcional. Exemplo:
    
    - Um campo de busca (input + botão)
    - Um label com input de formulário
3. **Organismos (Organisms)**
    
    São **grupos complexos de moléculas e/ou átomos** que formam uma seção identificável da interface. Exemplo:
    
    - Um cabeçalho com logo, menu e botão de login
    - Um card de produto com imagem, nome e preço
4. **Templates**
    
    São **layouts compostos por organismos**, organizados em uma estrutura de página, mas com **conteúdo genérico**. Eles mostram como os componentes funcionam juntos.
    
5. **Páginas (Pages)**
    
    São **instâncias reais dos templates**, com **conteúdo final e específico**. São úteis para testar a usabilidade e consistência visual.
    
    ![image.png](attachment:3524bc39-8e50-419b-892e-ab5e4644b452:image.png)
    

---

### Por que usar Atomic Design?

- Facilita **reutilização de componentes**
- Promove **consistência visual**
- Ajuda no trabalho colaborativo entre **designers e desenvolvedores**
- Melhora a **manutenção e escalabilidade** de projetos grandes

Se quiser, posso te mostrar um exemplo visual para cada etapa ou te ajudar a aplicar essa metodologia em um projeto seu.

## Átomos

![1_RdbLlQS0RpmRQ3Bw5hJbxA.webp](attachment:ad5b1b53-00ae-4642-baaa-29e5c67357e8:1_RdbLlQS0RpmRQ3Bw5hJbxA.webp)

Eles são os primeiros elementos a serem criados em um site, são as partes basicas,  por exemplo:

![image.png](attachment:81de638f-06bc-45e7-91a6-f21f74da3156:image.png)

![image.png](attachment:02ae12e6-607f-41f8-a0dd-df6becc8a1d9:image.png)

## Moléculas

![1_OHeV_LO3mGilt7z60RHPgA.webp](attachment:90998339-0839-4379-aa08-c08427438eea:1_OHeV_LO3mGilt7z60RHPgA.webp)

Elas são conjuntos de átomos, ou elementos em um site, por exemplo: 

## Organismos

![1_lfP46ddcd2kOjg4Ce8ZhgA.webp](attachment:0e2f72e6-c7f4-41cd-b683-db810a178326:1_lfP46ddcd2kOjg4Ce8ZhgA.webp)

Conjuntos de moléculas, formando um organismo, como main, section e header, por exemplo:

## Templates

![1_e8nZjPozJoPZ_NjgR6M1WQ.webp](attachment:1f16e995-0877-4de1-a779-0023b6abc9fb:1_e8nZjPozJoPZ_NjgR6M1WQ.webp)

Templates são praticamente páginas prontas, porém, sem conteúdo, podem ser utilizadas para mais de um site.

## Páginas

![1_-BCQkJ587iBYwue-SNrTYw.webp](attachment:f5dffcb0-f596-4009-902d-fda6f8a63b8f:1_-BCQkJ587iBYwue-SNrTYw.webp)

Páginas são um site já completo.
