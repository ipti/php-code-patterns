# php-code-patterns

# PHPMD
**Reference:** [PHP MESS DETECTOR RULES](https://phpmd.org/rules/index.html)
## CLEAN CODE RULES
- **BooleanArgumentFlag:** Não devem ser passados como parâmetros de uma função, argumentos do tipo boolean com valor default.
- **StaticAccess:** Não declarar métodos com acesso estático `Method::method()`
- **IfStatementAssignment:** Não fazer atribuições de valor a variáveis em estruturas condicionais `if`
- **DuplicatedArrayKey:** Não definir um novo valor para uma chave de um array que já possui um valor atribuído.
- **ErrorControlOperator:** Não utilizar o operador de erro `@`
- **MissingImport:** Deve importar todas as classes externas através de instruções de uso, as tornando visíveis
- **UndefinedVariable:** Não utilizar variáveis que não foram definidas anteriormente.

## CODE SIZE RULES
- **CyclomaticComplexity:** Manter um limite de 10 pontos de decisão em uma função, para não torná-la muito complexa.
- **NPathComplexity:** Manter um limite de 200 resultados possíveis para um único método.
- **ExcessiveMethodLength (70):** Manter um limite de 70 linhas de código por método. Caso seja necessário, tente distribuir o método criando métodos auxiliares e removendo possíveis códigos duplicados.
- **ExcessiveClassLength (800):** Manter um limite de 800 linhas de código por classe. Caso seja necessário, tente dividí-la em outras classes ou métodos.
- **ExcessiveParameterList (4):** Manter um limite de 4 parâmetros por método. Caso seja necessário, tente agrupar os parâmetros.
- **ExcessivePublicCount (30):** Manter um llimite de 30 métodos por classe.
- **TooManyFields(15):** Manter um limite de 15 campos por classe. Case seja necessário, a classe deve ser reprojetada para ter menos campos, agrupar os campos pode ser uma solução. 
- **TooManyMethods (25):** Manter um limite de 25 métodos para uma única classe.
- **TooManyPublicMethods (10):** Manter um limite de 10 métodos públicos para uma única classe. 
- **ExcessiveClassComplexity (50):** Manter um limite de 50 pontos de decisão no total para todos os métodos em uma classe.

## CONTROVERSIAL RULES
- **CamelCaseClassName:** Use `camelCase` para declarar nome de classes.
- **CamelCasePropertyName:** Use `camelCase` para declarar nome de propriedades de classes.
- **CamelCaseMethodName:** Use `camelCase` para declarar nome de métodos.
- **CamelCaseParameterName:** Use `camelCase` para declarar nome de parâmetros
- **CamelCaseParameterName:** Use `camelCase` para declarar o nome de variáveis. 

## DESIGN RULES
- **ExitExpression:** Não utilizar o método `exit()` durante a execução do algoritmo
- **EvalExpression:** Não utilizar o método `eval()`, uma vez que pode gerar um risco de segurança.
- **GotoStatement:** Não utilizar o método `goto`, uma vez que dificulta a compreensão do código e prejudica o fluxo de controle da aplicação.
- **NumberOfChildren(15):** Manter o máximo de 15 "filhos" por classe. Um número excessivo de filhos para uma classe sugere uma árvore de hierarquia desequilibrada.
- **DepthOfInheritance(6):** Manter o máximo de 6 "pais" acima de uma classe. Um número excessivo de pais sugere uma árvore de hierarquia desequilibrada.
- **zCouplingBetweenObjects(13):** Manter o máximo de 13 dependências por classe.
- **zDevelopmentCodeFragment:** Não manter funções como `var_dump()` ou `print_r()` escritas ao longo do código, mesmo que estejam comentadas. 
- **EmptyCatchBlock:** Não utilizar `try-catch` vazios, mesmo que o seu uso seja justificado como correção de algum erro no sistema.
- **CountInLoopExpression:** Não utilizar as funções `count` ou `sizeof` em expressões de loop. Uma vez que pode se tornar uma fonte potencial de muitos bugs.

## NAMING RULES
- **LongClassName(max: 40):** Declarar classes com nomes de no máximo 40 caracteres e no mínimo 3 caracteres.
- **ShortClassName(min: 3):** Declarar classes 
- **LongVariable(max: 20):**
- **ShortVariable(min: 3):**
- **ShortMethodName(min: 3):**
- **ConstrutorWithNameAsEnclosingClass:**
- **ConstantNaming:**

## UNUSED CODE RULES
- **UnusedPrivateField:**
- **UnusedLocalVariable:**
- **UnusedPrivateMethod:**
- **UnusedFormalParameter:**


