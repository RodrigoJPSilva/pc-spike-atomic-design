<img width="1040" height="583" alt="image" src="https://github.com/user-attachments/assets/9708371e-554e-459e-95b4-37a7f26df52a" />

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
    

---

### Por que usar Atomic Design?

- Facilita **reutilização de componentes**
- Promove **consistência visual**
- Ajuda no trabalho colaborativo entre **designers e desenvolvedores**
- Melhora a **manutenção e escalabilidade** de projetos grandes


## Átomos

<img width="490" height="243" alt="image" src="https://github.com/user-attachments/assets/fc46734b-9bdd-4328-a89c-5ad33d7b3953" />

Eles são os primeiros elementos a serem criados em um site, são as partes basicas,  por exemplo:
Elementos e padrões de cores e botões, ou em outras palavras, tokens de design

<img width="494" height="521" alt="image" src="https://github.com/user-attachments/assets/c5504408-152e-4bc6-9480-aee3f4ff4b6e" />


## Moléculas

Elas são conjuntos de átomos, ou elementos em um site, por exemplo: 

## Organismos

Conjuntos de moléculas, formando um organismo, como main, section e header, por exemplo:

## Templates

Templates são praticamente páginas prontas, porém, sem conteúdo, podem ser utilizadas para mais de um site.

## Páginas

Páginas são um site já completo.
